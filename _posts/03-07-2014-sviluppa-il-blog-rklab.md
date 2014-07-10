---

layout: post
title: Sviluppa tu stesso questo sito
description: Modifica tu stesso il template del blog rklab!

---

Come ho già detto nell'articolo introduttivo, questo sito può essere modificato attraverso github e teoricamente attraverso uno dei vostri contributi potreste editare completamente il template che genera il blog facendogli assumere una nuova forma. __La domanda è quindi *Come?*__

##Quattro semplici passi

Inutile dire che requisito fondamentale, e pressoché unico, per editare a piacimento questo sito è quello di avere un account di [Github](https://github.com/join).

###Primo passo: Fork

Il primo step da compiere è quello di visitare il repository dove è contenuto il [template](https://github.com/rkpasia/rklab) del blog. 

Caricata la pagina, basterà cliccare il pulsante __Fork__ che si trova in alto a destra della pagina.

![Fork repository rklab](http://www.rklab.it/assets/img/fork.png)

Premendo il pulsante creerete un vostro nuovo repository direttamente collegato a quello del template del blog. 
All'interno saranno già presenti tutti i file che compongono il template.

####Il branch master

All'interno di questo branch sono contenuti tutti i file che compongono il template del blog.

####Il branch gh-pages

All'interno di questo branch sono contenuti i file compilati attraverso l'utilizzo di [Jekyll](http://jekyllrb.com)

###Secondo passo: Clone

Per scaricare sul vostro computer i file del repository che avete appena *forkato* dovete clonare il repository stesso.

Per farlo potete copiare l'url del repository ed eseguire il comando `git clone <url del repository>`, clonare attraverso l'applicazione di github o fare il download dei file .zip.

![clone repository rklab](http://www.rklab.it/assets/img/clone.png)

###Terzo passo: Edit

Quando avrete clonato in una cartella sul vostro computer il repository, potrete iniziare a modificare a vostro piacimento il template del blog. 

Per editare ed utilizzare il template sarà necessario conoscere come utilizzare Jekyll e Sass.

Finite le modifiche fate un __commit__ di esse e il __push__ nel repository sul server di github.

###Quarto ed ultimo passo: Pull request

Nella pagina del repository [originale](http://www.github.com/rkpasia/rklab/) andate nella sezione __pull request__ e create una nuova pull request. 

Dovete comparare il vostro repository che avete forkato e modificato (*nel branch master*) con quello originale, ovvero *rkpasia/rklab*.

Selezionata la sorgente originale e la sorgente modificata github visualizzerà tutte le modifiche che avete effettuato al template. 

Premete il pulsante *create pull request* ed il gioco è fatto.

##Accettare Pull request

Qui entrerò in gioco io, che potrò visualizzare i cambiamenti che avete effettuato e valutare se sono positivi o negativi per il bene del blog. 

Se saranno accettate le modifiche il vostro codice entrerà a fare parte del template che genera il sito e le modifiche verranno applicate online.

