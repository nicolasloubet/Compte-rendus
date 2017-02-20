# Blockchain dans la transition énergétique 

<p align="center">
<img src="https://github.com/nicolasloubet/Compte-rendus/blob/master/Images/blockchain-transition-energetique-slide1.jpg" width="80%">
</p>

# À propos de ce document

Ce document est une synthèse écrite - partielle - d'un [meetup](https://www.meetup.com/fr-FR/DAISEE/events/237689856/) organisé le 16/02/2017 au [Square](https://twitter.com/squareparis?lang=fr), initié par la [Fabrique des Mobilités](http://wiki.lafabriquedesmobilites.fr/wiki/Accueil), [DAISEE](http://daisee.org) et [Asseth](http://asseth.fr) dans le cadre des événements satellites de la conférence [EDCON](http://edcon.io) (les 17 et 18/02/2017).

# Présent.e.s sur place

* **[Mathieu](https://www.linkedin.com/in/matthieuboisson/)** : anc. *product owner* chez [PowerNext](http://www.powernext.fr/). Intéressé par les enjeux de traçabilité. 

* **Mikhaël** : designer ([Enzyme&Co](http://enzymeandco.com)). Curieux et en découverte des pratiques blockchain.

* **Johan** : ancien d'[Etalab](https://www.etalab.gouv.fr/qui-sommes-nous). Développe l'[OGP Toolbox](http://ogptoolbox.org/). Intérêt : modèles de gouvernance. 

* **[Sara](https://www.linkedin.com/in/sara-tucci-piergiovanni-1582672/)** : chercheure. au [CEA L](http://www-list.cea.fr/)[IST](http://www-list.cea.fr/) (CEA Tech), en charge activités / projets autour de la blockchain. Le CEA Collaboration avec l'[IRISA](https://www.irisa.fr/) de Rennes (sur les algorithmes de consensus), l'[IMT](http://www.telecom-sudparis.eu/fr_accueil.html) (sur les contracts). Le CEA explore les systèmes d'obligation au dessus de la blockchain. Sara cherche des personnes avec qui travailler.

* **Önder** : collègue de Sara. Spécialiste des systèmes et calculs distribués et intelligents

* **Jean-Baptiste** : co-fondateur de Mobion (location de scooters électriques). A connu le meetup via F. Gaisnier (engagé sur la Fabrique). Projet "Blockchain" sur l'infrastracuture de recharge des scooters.

* **[Valentin](https://www.linkedin.com/in/valentin-lombardi-83a3b5b6/)** : chargé d'innovation chez [Sigfox](https://www.sigfox.com/fr). A cherché des usecases pertinents au croisement IoT/Blockchain. A fouillé plusieurs domaines industriels mais n'a encore rien initité sur/autour de l'énergie.

* **David** : membre du [P2P FoodLab](https://p2pfoodlab.net/) (qui s'intéresse à l'agro-écologie). Il travaille sur robot pour jardiner des cultures maraichères. S'intèresse à DAISEE au travers des enjeux d'autonomie énergétique.

* **Kim** : dev web. S'intéresse à la BC, l'IoT et [IPFS](https://ipfs.io/). Contributrice DAISEE sur la partie API.

* **Stéphane** : dev web très engagé sur la blockchain. A travaillé - en stage - chez Ledger (qui développe des *hardware wallets*). Co-fondateur de [ASSETH](http://www.asseth.fr/). A créeé sa société de conseil pour former des équipes. 

* **Jean-Mickael** : étudiant à l'[ESIEE](http://esiee.fr). Travaille actuellement sur un projet qui s'appuie sur [IOTA](https://iotatoken.com/) (pour des pratiques d'audit). Intéressé par les enjeux techniques de l'énergie. Également membre d'[ASSETH](http://www.asseth.fr/)

* **Martin** : étudiant à [SUPAERO](https://www.isae.fr/). Intéressé par le secteur de l'énergie. Présent par curiosité ! 

* **Anna** : travaille chez [Energisme](http://energisme.com/fr/) (qui compte 30 personnes). Doctorante sur la thématique. 

* **[Pierre](https://www.linkedin.com/in/paperon/)** : stratégiste. A connu les débuts de l'Internet (grand public). Suit Bitcoin depuis 2013 et s'intéresse depuis 2014 au 'Blockchains 2.0". Investisseur dans différentes sociétés dont [Energisme](http://energisme.com/fr/) (impliqué sur un "POC" pour Bouygues). Intéressé par les apports de la blockchain Ethereum en matière de gouvernance. 

* **Julien & François** : co-fondateurs de [Tallium](http://www.talium.fr/) qui a réalisé 2 'POCs' pour SunChain.

* **Samira** : tech leader de DAISEE. Soutient toutes les démarches des prototypage.

* **Nicolas & Clément** : explorateurs, co-initiateurs de [Cellabz](http://cellabz.com) qui co-produit DAISEE.

* **Rieul** : énergéticien de métier, co-initiateur de la [MYNE](http://lamyne.org) qui co-produit DAISEE.

# Intervention de Julien

[Talium](http://tallium.fr) a déployé 2 usecases pour SunChain (spin-off de [TECSOL](http://www.tecsol.fr), spécialiste de l'énergie photovoltaique en France).

* Auto-consommation d'énergie avec [Monax](https://monax.io/?redirect_from_eris=true) 

<p align="center">
<img src="https://github.com/nicolasloubet/Compte-rendus/blob/master/Images/blockchain-transition-energetique-slide2.png" >
</p>

* Consommation "mobile" avec [Hyperledger](http://hyperledger.org)

<p align="center">
<img src="https://github.com/nicolasloubet/Compte-rendus/blob/master/Images/blockchain-transition-energetique-slide3.png" >
</p>

Vont rencontrer ENEDIS bientôt pour questionner le coût de passage sur le réseau (centralisé).

Point intéressant : il y a d'autres projets que Fabric dans Hyperledger : cello, iroha, etc.

**Action** : soutenir leur recherche de profils qui ont de la pratique sur/avec blockchain (ils recrutent  !).

# Intervention de Sara

CEA Tech est le pole de recherche technologique du CEA (qui agit historiquement en support à la gestion des centrales). Expertise coeur : la vérification de programmes (pour des installation industrielles critiques).

La recherche 'blockchain' s'inscrit dans la branche "systèmes distribués", vérification, algorithmie. Les activités de recherche portent sur les Smart contracts et le Networking (réseau, détection de failles).

Philosophie blockchain : chacun peut contribuer au système. E.g. dans une "Supply Chain", il y a pas mal de compétiteurs qui ne peuvent pas se faire confiance. Blockchain => j'ai fait quelque chose, tout le monde le sait. 

Comment améliorer les services à partir des traces laisssées sur la blockchain ? > data analytics

Très dur d'évaluer toutes les techniques (= maîtriser, comparer, savoir ce qu'il y a derrière...).

Panel de technologies présentées sur le meetup : 
*   Cryptographie homomorphe
*   Exhaustive vulnerability detection. 
*   Network Security

IRISA est l'un des laboratoires spÈcialistes (en EU) dans le domaine du calcul distribué.

Startup intégrée dans le processus de travail autour de la thématique  **[Trust In Soft](https://trust-in-soft.com/about-us-tis/)**.

**Action** : lien avec les core devi Ethereum (pendant [EDCON](http://edcon.io) !) => voici le [diaporama](https://www.dropbox.com/s/kxm5mthqw3l5p5f/Block-chain%40CEA_LIST4Meetup_2017.02.15.pdf?dl=0). 

# Intervention de J.-B.

Objectif : qualifier l'énergie qu'on consomme / produit. Interaction telecom / blockchain.

Mission : avoir un instantané de la qualité du réseau. Partage d'une "méta-variable".

Conseil de Matthieu : voir les "garanties d'origine" (Powernext est l'un des garants en FR).

# Intervention de Pierre

Panel d'exp. micro-grid (Brooklyn Microgrid, Confluence). Recommande de suive Veolia.

S'intèresse surtout aux nouvelles citoyennetés, démocratie peer to peer (à l'échelle locale).

Pour un aperçu des travaux de Pierre, voir : [](http://observatoire-blockchains.com)http://observatoire-blockchains.com

# Intervention de Rieul

<p align="center">
<img src="https://github.com/nicolasloubet/Compte-rendus/blob/master/Images/blockchain-transition-energetique-slide4.jpg" width="80%">
</p>

Rieul a fait la même présentation que sur EventHorizon : [](http://bit.ly/DAISEE-EventHorizonx)http://bit.ly/DAISEE-EventHorizonx

# Crédits images

*   La photo en une de ce document a été prise par [Charlotte Rizzo](https://www.linkedin.com/in/charlotte-rizzo-39651124/) (la MYNE) et publiée sur [Twitter](https://twitter.com/ch4r1zz/status/808609721490014208) le 13 décembre 2016.
