
Let $G=(N,A)$ be a directed network with a cost $c_{ij}$ and a capacity $u_{ij}$ with every arc $(i,j)\in A$. For every node $i \in N$, let $b_{i}$ be the supply or demand. The minimum cost flow problem can be stated as follows \textbf{MCFP}:
$$
\begin{array}{lll}
\min & \sum\limits_{(i,j)\in A} c_{ij}x_{ij} & \\
\text{s.t. } \sum\limits_{j:(i,j) \in A} x_{ij} - \sum\limits_{j:(j,i) \in A} x_{jij} = b_i, & i \in N, \\
& 0 \leq x_{ij} \leq u_{ij} & (i,j) \in A.
\end{array}
$$
Before solving this problem, we make the following assumptions:
\begin{enmuerate}
\item All data are integral (if there exists the rational numbers, it could be convert to integeral by multiply);
\item The network is directed (if it is undirected, we could construct the corresponding directed arc $(i,j),(j,i)$ );
\item \sum\limits_{i\in N} b_i =0
\end{enumerate}
