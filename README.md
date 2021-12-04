#  treedrawing
Naive Rooted Tree Drawing Algorithm in Python 3

### The objective is simple. From this . . .

![Input Tree Data](./images/input.png)

### . . . to this!

![Output Tree Drawing](./images/output.png)

Of course, the tree data above is just an example. Input tree can be a "pointer" to database, spreadsheet, etc.

Parts of the algorithm are recursive. Hence, expect the performance to be slower and memory-intensive for larger trees.

#### Algorithm Description & Proof of Correctness
https://github.com/poypoyan/matematex/blob/main/treedrawing.pdf

#### TODO
- Proof that no branches/edges would intersect (PDF & TEX)
- Drawing of edited input tree
- Port on a language with tail-call optimization

#### Installation & Tutorial
1. Just download the ZIP for this repository, extract to a folder.
2. Just run `python example.py` (Windows) or `python3 example.py` (Lunix) in your terminal.
3. The `example.py` contains information on how to use `tdcore.py`.

Found a bug? Suggest a feature? Please post on [issues](https://github.com/poypoyan/tree_drawing/issues).
