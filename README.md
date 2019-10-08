# TTTTRPG
**Timeline Tree of Tabletop Role-Playing Games, celebrating more than 40 years of game design innovations**

Over 1000 ttrpg and 800 game designs, webbed through 1500 links. From 1974 to 2019.

* Download the **[PDF poster](https://github.com/pmartinolli/TTTTRPG/blob/master/files/ttttrpg.pdf)** (4 Mo)

[![TTTTRPG snapshot](https://github.com/pmartinolli/TTTTRPG/blob/master/files/ttttrpg-snapshot.png)](https://github.com/pmartinolli/TTTTRPG/blob/master/files/ttttrpg.pdf)

## How to... 

### ... Do it myself 

* Download the latest [source code](https://github.com/pmartinolli/TTTTRPG/blob/master/files/ttttrpg.gv). It should be easy to understand, but you can read more [explanations](https://jdr.hypotheses.org/919) of the structure of the source code. 
* Download the [zip package of icon pictures](https://drive.google.com/open?id=1N30n0QYaGSWLJTzJwPzn3wuklmib3zI8). Unpack the pictures in a folder C:/gv/ on your computer.
* Install and set up [Graphviz and Textpad++](http://zotrpg.blogspot.com/2016/05/creating-graph-for-od.html).
* Compile the code. The details are in the header of the [source code](https://github.com/pmartinolli/TTTTRPG/blob/master/files/ttttrpg.gv) ("Parameters"). It will produce a ps file.
* With Adobe Distiller, turn the ps file into a PDF file. If you successfully used a free and open-source software to do that job, please let me know. 

### ... Contribute

* Send me corrections or suggestions at pascal.umontreal [at] gmail.com 
  * It can take time before I answer you.
  * If you don't want to be cited as contributor, add "no citation" in your email.
  
* Improve [Wikidata](https://www.wikidata.org) items related to tabletop RPG. 
  * I documented some guidelines here https://www.wikidata.org/wiki/Wikidata:WikiProject_Board_Games (contact me at [Pmartinolli](https://www.wikidata.org/wiki/User:Pmartinolli) if you need help). I already made 7000 edits on TTRPGs so I have a little understanding of what is what there.
  * Why Wikidata ? I try to mirror as much of the informations as I can on Wikidata to benefit from the database tools and from the community of contributors. [Click here](https://query.wikidata.org/#%23defaultView%3AGraph%0ASELECT%20%3Fitem%20%3FitemLabel%20%3Fcited_works%20%3Fcited_worksLabel%20%0AWHERE%0A%7B%0A%20%20%20%20%3Fitem%20%20wdt%3AP31%20wd%3AQ1643932%20.%20%20%20%23%20instance%20%3D%20ttrpg%0A%20%20%20%20%3Fitem%20%20wdt%3AP2860%20%20%20%20%3Fcited_works%20%20.%20%20%20%23%20which%20cites%20works%0A%20%20%20%20%3Fcited_works%20wdt%3AP31%20wd%3AQ1643932%20%20%20%20%20%20.%20%20%20%23%20that%20are%20TTRPG%20%20%0A%20%20%20%20SERVICE%20wikibase%3Alabel%20%7B%20bd%3AserviceParam%20wikibase%3Alanguage%20%22en%22%20%7D%0A%7D%0A) to have a graph of the citation practices in TTRPG. 
  
* Export the data into [GEPHY](https://gephi.org/). Why ? 1) I want to try it ; 2) I think the database structure of GEPHY can help managing all the informations ; 3) It's open source.

### ... Start my own project

* Have a look on this simple [template](https://github.com/pmartinolli/TTTTRPG/blob/master/files/template.gv) of the graph, and on the [rendering](https://github.com/pmartinolli/TTTTRPG/blob/master/files/template.png).
* Gather your friends (or your students) and decide some teamwork methods. Each of you create an account on GitHub. 
* Deposit your files on GitHub.
* Go!
* Don't forget to be a gentleman/gentlelady of the open access : cite me and Todd Lehman.

### ... Thank me

- Tweet it [@pascaliensis](https://twitter.com/Pascaliensis).
- Comment it on your social media.
- Cite me it your academic work : `Martinolli, Pascal. 2019. « Timeline Tree of Tabletop Role-Playing Games, celebrating more than 40 years game design innovations. » Dataset and dot language code. https://github.com/pmartinolli/TTTTRPG`
- Print it and display it in your school, library, exhibition, etc.
- Send me an email : pascal.umontreal [at] gmail.com

## Acknowledgements 

The source code is an adaptation of the code created by [Todd Lehman](https://tex.stackexchange.com/users/8499/todd-lehman) for his [“TeX Family Tree”](https://tex.stackexchange.com/questions/42594/tex-family-tree-with-timeline). 

The data sources of this work are numerous. You can have a look of the [references](https://github.com/pmartinolli/TTTTRPG/blob/master/files/ttttrpg-sources.md) used to select, check and analyze the TTRPGs.

This timeline is a part of the « [On the Shoulders of Dwarves](http://zotrpg.blogspot.com/search/label/on%20the%20shoulders%20of%20dwarves) »[(fr)](https://jdr.hypotheses.org/category/sur-les-epaules-des-nains) set of projects .

### This content is CC-BY-NC-SA 4.0 

Informations in the source code are pure facts, therefore they cannot be copyrighted. The curation of these informations, the links between them and the structure of their display are a work of edition. For this reason, I will be glad you aknowledge my name if you want to reuse them.


## Metadata / Métadonnées

* Author / Auteur : Pascal Martinolli

* Created / Créé le : 2016

* Most recent version / Dernière version : 2019-10-01

* Original format / format de fichier : Graphviz Dot (Open source)

* License / Licence : [CC-BY-NC-SA](https://creativecommons.org/licenses/by-nc-sa/4.0/)

* Presented at, promoted through / Présenté à, diffusé via : [Donjons & Données probantes 2018](http://hdl.handle.net/1866/21088), [Blogue Jeu de rôle sur table](https://jdr.hypotheses.org/category/graphe), [ZoTrpg blog](https://zotrpg.blogspot.com/search/label/timeline), [ResearchGate](https://www.researchgate.net/publication/333489073_Timeline_genealogic_and_phylomemetic_tree_of_role-playing_game_designs_Celebrating_40_years_of_game_innovations_from_1974_to_2019_partially_released), [Academia](https://www.academia.edu/39317882/Timeline_genealogic_and_phylomemetic_tree_of_role-playing_game_designs_Celebrating_40_years_of_game_innovations_from_1974_to_today_partially_released_), [Twitter](https://twitter.com/Pascaliensis/status/1177314806442921985).

* Contributors (sor far) : People and works cited in the [references](https://github.com/pmartinolli/TTTTRPG/blob/master/files/ttttrpg-sources.md), Éric Nieudan, Steve Dempsey, James Wallis, Veso_M.

* Commments and collaborations are welcomed at / Commentaires et collaborations bienvenus : pascal.umontreal [at] gmail.com



\
\
https://github.com/pmartinolli/TTTTRPG
