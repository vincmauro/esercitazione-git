Branching è un'operazione di creazione di un nuovo branch a partire da master (o main, nelle ultime versioni). Per creare un nuovo branch fare:
git checkout -b <nomebranch>
Per spostarmi in un nuovo branch fare:
git checkout <nomeBranch>
Per sapere in quale branch mi trovo fare 
git branch
Per vedere tutti i branch fare:
git branch -a

Il merging è l'operazione di unione di due branch e lo si può fare così
git merge <nome>
o anche 
git merge --no-ff <nome>.