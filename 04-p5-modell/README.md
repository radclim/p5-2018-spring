# A p5 modell  

Ma megtanulunk mozgó, sőt interaktív programokat írni.  


A p5 programok utasításai három blokkra vannak osztva: felkészülés - folyamat - reakció. A blokkok hivatalos neve: `setup`, `draw`, illetve a megadott történés neve: `mouseClicked`, `keyPressed` stb.  

Írjunk vízcsepp-programot: egy kicsi, kék sprite elindul a vászon tetejéről, és lecsúszik - kattintásra pedig ugorjon vissza a vászon tetejére.  
Teljesen üres sablon: https://gist.jsbin.com/endreymarcell/3202d6218443402331c6f374b158ee3a  






Ötletek további mozgó programokra:  
__Fény az alagút végén__  
A vászon közepén létrejön egy 1*1-as méretű sprite, és elkezd nőni, de billentyűnyomásra visszaugrik az eredeti méretére. A vászon legyen fekete, a sprite fehér.  
(Ha szeretnél még feladatot: tegyél be még egy sprite-ot a programba, ami szürke színű, és mindig 20 képpontal szélesebb és magasabb, mint a fehér.)  

__Kattraforgó__  
Zöld vászon közepén egy sárga sprite folyamatosan forog. Ha kattintasz a vásznon, a sprite pont oda ugrik, ahol épp az egér van, és forog tovább.  
(Ha ki szeretnéd egészíteni: tegyél bele még egy sprite-ot a programba, ami helyben mindig követi az előzőt, de kicsit kisebb, fekete, és az ellenkező irányba forog.)  

__Szobafestő__  
Létrejön egy sprite, ami aztán minden pillanatban oda megy, ahol épp az egér van. Azt is szeretnénk, ha a sprite nyoma nem tűnne el, mikor elmozdul, hanem csíkot húzna maga után - hogy tudod ezt megoldani?  
Ha szeretnéd, beleírhatod, hogy kattintásra viszont letörlődjön az egész vászon.  

(__Szobafestő a fürdőszobában__  
_Ez az előző program kiegészítése._  
Legyen a programban még egy sprite, ami tükörben mozog az első száma sprite-tal: függőlegesen ugyanott van, de vízszintesen tükrözve van a vászon másik oldalára. A második sprite helyét újra meg újra ki tudod számolni az első sprite helyéből - gondolkodj rajta, hogyan, vagy beszéld meg a mentoroddal.)  

__Valami__  
Hozz létre egy sprite-ot a vászon közepén, aztán minden pillanatban állítsd be a sprite méretét aszerint, hogy mi az egér aktuális x helye, a forgását pedig aszerint, hogy mi az y hely.  
(Ha még interaktívabb programot szeretnél, írd át a programot úgy, hogy a háttér ne fehér legyen, hanem az is az egér helyzetéből következzen, például az piros színkomponens lehet az egér x helyzete, a kék pedig az y.)  

__Graffiti__  
Egy üres, fehér vásznon létrejön egy sprite, aki aztán minden pillanatban véletlen helyre ugrik. Úgy írd meg a programot, hogy az ugrások között ne törlődjön le a vászon, de kattintásra igen.  
(Ha szeretnéd, beleírhatod, hogy minden ugráskor véletlen legyen a sprite 1. forgása, 2. színe, 3. mérete is.)  

__Csillagos__  
Egy üres, fekete vásznon létrejön egy sárga sprite véletlen helyen. A sprite legyen 100 képpont széles, de csak 1 képpont magas. Utána minden pillanatban állítsd véletlenre a sprite forgását, és ne töröld le a vásznat. Ha kattintasz, a sprite ugorjon az egér helyére.  
(Ezt még kiegészítheted azzal, hogy a sprite szélessége véletlenszerűen változik kb. 50-150 között, a magassága 1-3 között.)  

__Hanghullám__  
A sprite-od legyen 3 képpont széles, 1 képpont magas. Induljon a vászon bal széléről, függőlegesen középről. Minden pillanatban állítsd a magasságát véletlenre 0 és `height` között, és told vízszintesen jobbra három képponttal. A vásznat ne töröld le menet közben.  
(Ezt kiegészítheted azzal, hogy kattintásra letörlöd a vásznat, és visszahozod a sprite-ot a vászon bal szélére.  
Vagy, ha az jobban tetszik: kattintásra se töröld le a vásznat, viszont adj a sprite-nak új, véletlen színt.)  



Ha szeretnél még feladatot:  
__Sötétítő__  
Indíts egy fehér háttérrel, ami folyamatosan, szépen lassan besötétedik. Ezt úgy tudod megcsinálni, hogy majdnem teljesen átlátszó fekete színnel fested le a vásznat újra meg újra. Kattintásra váltson a vászon megint fehérre (hogy aztán újra elsötétülhessen).  