 ## Diseny i realització de probas 
  ### Introducció 
  #### Objectius de les probas
  - El principal objectiu de fer probas es sempre veure si el teu software no funciona com deberia de funcionar, 
 - Existeixen diferents Framework que s'utilitzen per realitzar les proves. 
 #### Framework 
Un Framework es un esquema que ens ofereix un entorn generic per a programar en algun llenguatje com pot ser java, c++, c#... 
un framework esta compost principalment per:
- eines comuns 
-  biblioteques 

un dels frameworks que s'utilitzen mes en entrons webs es Django que s'utilitza per a Python.

### Proves
#### Forma de les proves
Existeixen dos formes de proves: 
- Proves dinámiques: Les proves dinamiques són les proves que pots afegir diferents valors per veure diferents resultats i requereixen de la ejecució de la aplicació.  
- Proves estatiques: Són les proves en el que no s'exeucta la aplicació i es veu si hi ha algun error examinant el codi font.

#### Estrategias de prova 
En total hi ha dos estrategies de prova diferent:

- Caixa negra: En la caixa negra lo que es mira es el resultat final es a dir la funcio que te la aplicació sense preocuparse del seu codi.
- Caixa blanca: No es mira el funcionament del codi pero s'examina el seu codi font per comprovar si la ejecució i la seva estructura són correctes.

#### Estrategias de prova Caixa Negra
- no es mira el funcionament intern 
- nomes es mira el resultat final 
- es traballa sobre la interficie 
- Les principals tecniques son:
    - Particions de equivalencia 
    - Valors límit 
#### Estrategias de prova Caixa Blanca
- S'examina el codi font 
- Es comprova que l'estructura del codi estigui correcta 
- Les principals tecniques son:
    - Cobertura de codi 
    - Proves de bucle 

#### Tipus de proves 
Els tipos de proves que hi ha són: 
- Funcionals: Les proves funcionals són les proves en el que es mira més el resultat final que com estigui format el codi un exemple d'aixó seria la caixa negra. 
- No funcionals: Les proves no funcionals són les proves que es miran tots els aspectes interns com el aspecta del codi, si es facil de llegir, si te un estructura correcta, el seu rendiment... un exemple seria la caixa blanca encara que no seria del tot  perque no compleix totes les restricions de no funcional.

#### Proves Funcionals 
Les diferents proves funcionals son:
- Proves unitaries: Les proves unitaries consisteix en apartar una part del codi i comprovar que funcioni tot correctament.
- Proves de regresió: les proves de regresió es fan cada vegada que es canvia de sistema per afegir millores o solucionar errors. 
- Proves de integració: Es realitzan per comprovar com els moduls que funcionan de forma individual funcionan cuan esta tot integrat en el mateix codi. 
- Proves de fum: Les proves de fum es una revisió rapida del software per comprovar que tot funcioni correctament i no hi hagi ningún error evident. 
- Proves del sistema: Te el objectiu de verificar que el software s'ha integrat correctament al sistema. 
- Proves alfa i beta: Són proves que es separan en dos parts la alfa que seria proves que fa el programador utilitzant el programa i veient que tot funciona correcteament i seguidament el beta que són proves que fan els clients encara que nomes una part molt reduida del public general si hi ha algun problema ho informan perque s'arregli. 
- Proves d'aceptació: Les proves d'aceptació lla es la ultima part de les proves de funcionament i s'utiltizen aquestes proves per veure el grau d'acceptaciò d'un producte al public genarl. 
#### Proves no Funcionals
- Proves de usabilidat: Són proves que es fan per veure lo faci o comode que es utilitzar el software.
- Probes de rendiment: Són proves que s'utilitzant per mirar el rendiment del software es a dir mira la velocitat de execució, cuan tarda el programa en obrirse... 
- Proves de stress: Són proves que es fan per veure la reacció de la empresa si passes alguna crisis.
- Proves de seguretat: Son proves que s'utilitzen per medir la seguretat del software i que sigui segur per a la venda al public.
- Proves de compatiblidat: Són proves que es realitzen per veure si el software es compatible amb el sistema operatiu i tots els navegadors d'internet. 
- Proves de portabilitat: La proba de portabilitat es un proces que determina la facilitat o dificultat en la que un component de software pot transportarse de forma efectiva a un altre entorn opertiu.

#### Mecanisme de prova 
Hi ha dos mecanismes diferents són: 
- Manual: Són proves que es realitza manualment per algun empleat de la empresa o algú extern.
- Automatic: Són proves que es realitzen amb algun tipus de software que ejecuta el codi i compara els resultats amb els resultats que tindrian que ser.

### Integració
#### Formes de Integració 
Les formes de integració que hi ha són:
- Integració Big bang: Son un tipos de proves de integració en la que algun element hardaware, software o les dos son combinats de forma simultanea en un component o un sistema en lloc de fer-oh per fases.  
- Integració Descendent: La integració Descendent son unes probes que te un enfocament incremental de probes de integració on el compoment en el nivell mes alt de la jerarquia es probat en primer lloc. 
- Integració Ascendent: La integració Ascendent es molt semblant a la descendent nomes la unica diferencia es que els components de mes baix nivell son probats en primer lloc. 
- Integració Continua : La integració Continua consisteix en automatitzar un proces de integració de codi per a podder realitzar la operació de la manera mes continuada posible.
#### Servidor de Integració Continua 
Els diferens servidors que hi han són: 
- Jenkins: Es un servidor de automatització escrit en java. 
- Bamboo: Es una eina de integració continua que reuneix compilaicons, proves i versions automatitzades un un sol fluix de treball. 
- TravisCI: Travis CI es un servei de integració continua que s'utilitza per crear i provar projectes de software que estan en GitHub i Bitbucket. 
- CircleCI: CircleCi proporciona un soport i servei de clase empresarial i treballa amb sistemes Linux,macOs,Android i Windows 
#### Cobertura de codi
La cobertura de codi es un indicador del procentaje del codi total que has utilitzat, es recomana que s'utilitze lo mes aprop del 100% del codi total perque si no pot haber algun error hi ha que una part pot necessitar el codi que no se esta executant. 
### Qualitat
#### Control de Qualitat
Es necessari realitzar probes per probar la qualitat d'un producte
#### Qualitat del proces/producte(QA/QC)
- QA: La qualitat del proces es un conjunt d'activatats que garantitzan que aquell proces te una cualitat aceptable per a desenvolupar els productes. 
- QC: La cualitat de productes es un conjunt d'activitats que garantitzan la qualitat dels productes i aquestas activitats són de intentar trobar algun defecte si no el troben pot sortir al mercat i si no pasara per una revisió per arreglar el problema. 
#### Factors de Qualitat 
Els factors de qualitat es poden agrupar en 3 ambits:
- Operació del producte: Són les operacions que es fan sobre el producte. 
Les operacións del producte pasen per unes fasse que son:
    - Correció: Correció de errors
    - Fiabilitat: La confianza de que en aquell producte no apareixera per exempla anunci de virus que pugin danyar el teu ordinador.
    - Eficiencia: Reduir el codi tant com sigui possible i que no hi hagi tanta palla nomes lo necessari. 
    - Seguretat: Procurar que el programa sigui segur es a dir que ningu pugui entrar dins del programa i vigili lo que fan els clients.  
    - Facilitat d'us: Que no sigui complicat d'usar i sigui facil de aprendre anar. 
- Revisió del producte: Revisan que el producte no tingui ninguna falla 
    En la revisió de producte i han 3 fases que te que pasar: 
    - Mantenibilitat: Es la posibilitat de que el producte en cas de que falli pugui ser reparat.  
    - Flexibilitat: Vol dir que no es pugi utilitzar nomes per una cosa concreta si no que tingui varies formes d'us. 
    - Facilitat de probes: Que sigui sencill provar que el programa funciona correctament sense que tingui que complicar-te massa. 
- Transició del producte: Transportan el producte al client final
 En la transició del producte te que pasar per tres fases que són:
    - Portabilitat: Que sigui facil de portar i canviar de lloc  
    - Reusabilitat: es per exemples que si algu et dona el programa tu puguis donar-li a algu mes per que l'utilitzi i aquet altre lo mateix es a dir que no sigui nomes d'un us. 
    - Interoperativitat: Que sigui facil intercanviar la informació i utilitzar facilment la informació intercanviada 

