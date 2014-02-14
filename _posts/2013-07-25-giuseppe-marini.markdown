---
layout: intervista
date: 2013-07-25 00:01:00 Europe/Rome
categories: intervista
nome: "Giuseppe Marini"
short_description: "Sviluppatore per Era della Trasparenza"
tags: sviluppatore
ritratto: Giuseppe-Marini-332x357.jpg
ritratto_width: 332
ritratto_height: 357
postazione: Giuseppe-Marini2-332x268.jpg
postazione_width: 332
postazione_height: 268
postazione_alt: "La scrivania di Giuseppe Marini"
sitemap.lastmod: 2014-02-13
---


###Chi sei e di che cosa ti occupi?
Sono Giuseppe Marini, vivo a Roma con la mia famiglia e sviluppo software. Dopo una decennale esperienza con software cosiddetto commerciale in grandi aziende, oggi mi dedico con software libero all'analisi e sviluppo del progetto [Era della Trasparenza][1] della comunità che è [Agorà Digitale][2].

###Quali strumenti usi per il tuo lavoro?
L'architettura hardware del progetto *Era della Trasparenza* è composta da due unità fisiche: una dedicata a sviluppo e collaudo e l'altra dedicata alla produzione.

Le due unità si differenziano sia nelle prestazioni che nella configurazione logica: la prima è un semplice pc desktop, che si limita a conservare l'ultima versione software, mentre la seconda è un server preso a noleggio, di gran lunga più performante, nella quale esiste effettivamente la separazione logica fra DB server e WEB server.

Questa separazione consente di non appesantire con il lavoro di sviluppo e collaudo un unico server che è già sollecitato dall'accesso di utenti esterni. Inoltre questa configurazione garantisce più sicurezza e ci evita di rilasciare in produzione software che non sia stato precedentemente collaudato.

###Quale software?
Ad oggi, su ambiente Linux, abbiamo programmato delle shell per l'acquisizione e la lavorazione dei dati provenienti dalle Pubbliche Amministrazioni. Utilizziamo [MySQL][mysql] come database e [PHP][php] come linguaggio per lo sviluppo web.

Abbiamo già in mente, per una fase 2 di Era della Trasparenza, di utilizzare altro software che possa migliorare il servizio che offriamo alla comunità, allargando la partecipazione al mondo open source. Ma questo sarà una sorpresa tanto per voi, quanto per noi.

###Come miglioreresti quello che usi per lavorare?
Era della Trasparenza è un progetto ambizioso che intende allargare nonché premiare la comunità che già ci sostiene. È un progetto che, attraverso un monitoraggio trasparente delle scelte e delle voci di spesa delle Pubbliche Amministrazioni, vuole far avvicinare e partecipare il cittadino alla vita e alle scelte pubbliche e perché no, anche criticare costruttivamente. Ecco, se si potessero migliorare, uniformare, organizzare da un punto di vista temporale, nei contenuti e nella forma, i dati provenienti dalle P.A. in ottemperanza al dettato legislativo in materia di trasparenza, avremmo fatto un gran passo in avanti: oggi c'è troppo disordine dovuto alle diverse interpretazioni e ai diversi stadi di lavorazione compiuti da ogni singola Pubblica amministrazione.


[1]: http://www.eradellatrasparenza.it "Era della trasparenza"
[2]: http://www.agoradigitale.org "Agorà digitale"
[mysql]: https://www.mysql.it/ "Il database open source più diffuso al mondo"
[php]: http://php.net/ "PHP: Hypertext Preprocessor"
