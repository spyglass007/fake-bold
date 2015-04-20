# fake-bold
Macro to get fake bold shape of any character (especifically, mathrsfs)

\def\mathscrbf#1{
    \hbox{%
          \hbox to 0.25pt{$\mathscr{#1}$\hss}%
          \hbox to 0.25pt{$\mathscr{#1}$\hss}%
          \hbox to 0.25pt{$\mathscr{#1}$\hss}%
          \hbox{$\mathscr{#1}$}%
    }
}
