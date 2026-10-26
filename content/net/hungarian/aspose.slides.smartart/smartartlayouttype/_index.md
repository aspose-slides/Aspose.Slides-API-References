---
title: SmartArtLayoutType
second_title: Aspose.Sildes a .NET API referenciája
description: A SmartArt diagram elrendezéstípusát képviseli.
type: docs
weight: 10620
url: /hu/aspose.slides.smartart/smartartlayouttype/
---
## SmartArtLayoutType felsorolás

A SmartArt diagram elrendezéstípusát képviseli.

```csharp
public enum SmartArtLayoutType
```

### Értékek

| Name | Value | Description |
| --- | --- | --- |
| AccentProcess | `0` | A folyamat, idővonal vagy feladat, folyamat, munkafolyamat szekvenciális lépéseinek megjelenítésére. Jól működik az 1. és 2. szintű szöveg illusztrálásához. |
| AccentedPicture | `1` | Központi, fotószerű ötlet és a mellékelt ötletek megjelenítésére. Az 1. szintű felső szöveg a központi kép felett jelenik meg. A többi 1. szintű alakzat szövege a kis kör alakú képek mellett jelenik meg. Ez az elrendezés szöveg nélkül is jól működik. |
| AlternatingFlow | `2` | Információcsoportok vagy szekvenciális lépések feladat, folyamat, munkafolyamat esetén. Hangsúlyozza a csoportok közti kölcsönhatást vagy kapcsolatot. |
| AlternatingHexagons | `3` | Összefüggő ötletek sorozatát ábrázolja. Az 1. szintű szöveg a hatszögekben, a 2. szintű szöveg a alakzatokon kívül jelenik meg. |
| AlternatingPictureBlocks | `4` | Képek sorozatát mutatja fel felülről lejjebb. A szöveg váltakozva a kép jobb vagy bal oldalán jelenik meg. |
| AlternatingPictureCircles | `5` | Képek és szöveg kombinációja. A megfelelő szöveg a központi körökben jelenik meg, a képek váltakozva balról jobbra. |
| ArrowRibbon | `6` | Kapcsolódó vagy ellentétes koncepciók mutatása valamilyen összeköttetéssel, pl. ellentétes erők. Az 1. szintű szöveg első két sorát a nyilak szövegeként használja. A nem használt szöveg nem jelenik meg, de elérhető, ha az elrendezést módosítja. |
| AscendingPictureAccentProcess | `7` | Felfelé haladó képsorozat és leíró szöveg. Kisméretű szöveggel a legjobb. |
| Balance | `8` | Két ötlet összehasonlítása vagy kapcsolatuk bemutatása. Az 1. szintű szöveg első két sorának szövege a középpont egyik oldalának tetején jelenik meg. Hangsúlyozza a 2. szintű szöveget, amely legfeljebb négy alakzatot tartalmaz mindkét oldalon. A mérleg a legtöbb 2. szintű szöveget tartalmazó oldalra billen. A nem használt szöveg nem jelenik meg, de elérhető, ha az elrendezést módosítja. |
| BasicBendingProcess | `9` | Folyamat vagy szekvenciális lépések feladat, folyamat, munkafolyamat esetén. Maximalizálja a vízszintes és függőleges helyet az alakzatok számára. |
| BasicBlockList | `10` | Nem szekvenciális vagy csoportosított információs blokkok megjelenítése. Maximalizálja a vízszintes és függőleges helyet az alakzatok számára. |
| BasicChevronProcess | `11` | Folyamat, idővonal, szekvenciális lépések feladat, folyamat vagy munkafolyamat, vagy a mozgás/irány hangsúlyozásához. Az 1. szintű szöveg a nyíl alakzatban, a 2. szintű szöveg a nyíl alatti helyen jelenik meg. |
| BasicCycle | `12` | A szakaszok, feladatok vagy események folyamatos körkörös sorozata. Hangsúlyozza a szakaszokat vagy lépéseket a kapcsoló nyilak vagy áramlás helyett. Leginkább csak 1. szintű szöveggel a legjobb. |
| BasicMatrix | `13` | Összetevők és egészek közötti kapcsolat négyzetben. Az 1. szintű szöveg első négy sora a kvadránsokban jelenik meg. A nem használt szöveg nem jelenik meg, de elérhető, ha az elrendezést módosítja. |
| BasicPie | `14` | Bemutatja, hogyan alkotnak az egyes részek egészet. Az 1. szintű szöveg első hét sorának megfelelően egyenletesen elosztott szelet vagy kör alakzatok. A felső 1. szintű szöveg alakzat a kör többi részének kívül jelenik meg a hangsúlyozásért. A nem használt szöveg nem jelenik meg, de elérhető, ha az elrendezést módosítja. |
| BasicProcess | `15` | Folyamat vagy szekvenciális lépések feladat, folyamat, munkafolyamat esetén. |
| BasicPyramid | `16` | Arányos, összefüggő vagy hierarchikus kapcsolatok, a legnagyobb komponens alul, szűkülve felfelé. Az 1. szintű szöveg a piramis szegmenseiben, a 2. szintű szöveg az egyes szegmensek melletti alakzatokban jelenik meg. |
| BasicRadial | `17` | Központi ötlethez kapcsolódó kapcsolat egy körkörös áramlásban. Az 1. szintű szöveg első sora a központi alakzatnak felel meg, a 2. szintű szöveg a körülötte lévő kör alakzatoknak. A nem használt szöveg nem jelenik meg, de elérhető, ha az elrendezést módosítja. |
| BasicTarget | `18` | Tartalmazást, fokozatokat vagy hierarchikus kapcsolatokat mutat be. Az 1. szintű szöveg első öt sora egy körrel van társítva. A nem használt szöveg nem jelenik meg, de elérhető, ha az elrendezést módosítja. |
| BasicTimeline | `19` | Szekvenciális lépések feladat, folyamat vagy munkafolyamat, vagy idővonal információk mutatása. Mind az 1., mind a 2. szintű szöveg jól működik. |
| BasicVenn | `20` | Átfedő vagy összefüggő kapcsolatok ábrázolása. Az 1. szintű szöveg első hét sora egy körrel párosul. Ha négy vagy kevesebb sor van, a szöveg a körökben, ha több, akkor a körök kívül jelenik meg. A nem használt szöveg nem jelenik meg, de elérhető, ha az elrendezést módosítja. |
| BendingPictureAccentList | `21` | Nem szekvenciális vagy csoportosított információs blokkok. A kis kör alakzatok képek tárolására szolgálnak. Mind az 1., mind a 2. szintű szöveg jól illusztrálható. Maximalizálja a vízszintes és függőleges helyet az alakzatok számára. |
| BendingPictureBlocks | `22` | Képsorozat megjelenítése. Az alsó sarokban lévő doboz kis mennyiségű szöveget tartalmazhat. |
| BendingPictureCaption | `23` | Szekvenciális képsorozat. Az alsó sarokban lévő doboz kis mennyiségű szöveget tartalmazhat. |
| BendingPictureCaptionList | `24` | Képsorozat. A cím és leírás egy felhívó alakzatban jelenik meg minden kép alatt. |
| BendingPictureSemiTransparentText | `25` | Képsorozat. A félig átlátszó doboz a kép alsó részét takarja, és minden szintű szöveget tartalmaz. |
| BlockCycle | `26` | A szakaszok, feladatok vagy események folyamatos körkörös sorozata. Hangsúlyozza a szakaszokat vagy lépéseket a nyilak vagy áramlás helyett. |
| BubblePictureList | `27` | Képsorozat. Legfeljebb nyolc 1. szintű kép tárolható. A nem használt szöveg és képek nem jelennek meg, de elérhetők, ha az elrendezést módosítja. Leginkább kis-közepes mennyiségű szöveggel a legjobb. |
| CaptionedPictures | `28` | Képek több szintű szöveggel. Leginkább kis mennyiségű 1. szintű és közepes mennyiségű 2. szintű szöveggel a legjobb. |
| ChevronList | `29` | Folyamatok sorozata, amelyek egy átfogó munkafolyamatot alkotnak. Ellentétes folyamatok ábrázolására is alkalmas. Az 1. szintű szöveg az első bal oldali nyíl alakzatnak felel meg, a 2. szintű szöveg a megfelelő alakzatokhoz tartozó vízszintes allépéseknek. |
| CircleAccentTimeline | `30` | Események vagy idővonal információk sorozata. Az 1. szintű szöveg nagyobb kör alakzatok mellett jelenik meg, a 2. szintű szöveg kisebb körök mellett. |
| CircleArrowProcess | `31` | Szekvenciális elemek, minden elemhez kapcsolódó szöveg. Ez a diagram leginkább kis mennyiségű 1. szintű szöveggel a legjobb. |
| CirclePictureHierarchy | `32` | Hierarchikus információ vagy szervezeti jelentési kapcsolatok. A képek körökben, a hozzájuk kapcsolódó szöveg a képek mellett jelenik meg. |
| CircleRelationship | `33` | Kapcsolat központi ötlethez vagy onnan. A 2. szintű szöveget nem szekvenciálisan adhatjuk hozzá, legfeljebb öt elem. Csak egy 1. szintű elem lehet. |
| CircularBendingProcess | `34` | Hosszú vagy nem lineáris sorozat vagy lépések feladat, folyamat, munkafolyamat. Leginkább csak 1. szintű szöveggel a legjobb. Maximalizálja a vízszintes és függőleges helyet az alakzatok számára. |
| CircularPictureCallout | `35` | Központi ötlet és alötletek vagy kapcsolódó elemek. Az első kép szövege a kép alsó részét fedi. A többi 1. szintű alakzat szövege a kis kör alakú képek mellett jelenik meg. A diagram szöveg nélkül is jól működik. |
| ClosedChevronProcess | `36` | Folyamat, idővonal vagy szekvenciális lépések feladat, folyamat, munkafolyamat, vagy a mozgás/irány hangsúlyozása. A kezdő alakzat információjának hangsúlyozására használható. Leginkább csak 1. szintű szöveggel a legjobb. |
| ContinuousArrowProcess | `37` | Idővonal vagy szekvenciális lépések feladat, folyamat, munkafolyamat. Leginkább 1. szintű szöveggel, mivel minden 1. szintű szövegsor a nyíl alakzatban jelenik meg. A 2. szintű szöveg a nyíl alakzat kívül jelenik meg. |
| ContinuousBlockProcess | `38` | Folyamat vagy szekvenciális lépések feladat, folyamat, munkafolyamat. Leginkább minimális 1. és 2. szintű szöveggel a legjobb. |
| ContinuousCycle | `39` | A szakaszok, feladatok vagy események folyamatos körkörös sorozata. Hangsúlyozza az összetevők közti kapcsolást. Leginkább csak 1. szintű szöveggel a legjobb. |
| ContinuousPictureList | `40` | Összefüggő információcsoportok. A kör alakzatok képek tárolására szolgálnak. |
| ConvergingArrows | `41` | Ötletek vagy koncepciók, amelyek egy központi pontra konvergálnak. Leginkább csak 1. szintű szöveggel a legjobb. |
| ConvergingRadial | `42` | Koncepciók vagy összetevők kapcsolata központi ötlethez egy körkörös áramlásban. Az 1. szintű szöveg első sora a központi kör alakzatnak, a 2. szintű szöveg sorai a körülöttes téglalap alakzatoknak felelnek meg. A nem használt szöveg nem jelenik meg, de elérhető, ha az elrendezést módosítja. |
| CounterbalanceArrows | `43` | Két ellentétes ötlet vagy koncepció. Az 1. szintű szöveg első két sora egy nyílnak felel meg, és jól működik 2. szintű szöveggel. A nem használt szöveg nem jelenik meg, de elérhető, ha az elrendezést módosítja. |
| CycleMatrix | `44` | Kapcsolat központi ötlethez egy ciklikus előrehaladásban. Az 1. szintű szöveg első négy sora egy szelet vagy kör alakzatnak felel meg, a 2. szintű szöveg egy téglalap alakzatban a szelet vagy kör alakzat mellett jelenik meg. A nem használt szöveg nem jelenik meg, de elérhető, ha az elrendezést módosítja. |
| DescendingBlockList | `45` | Kapcsolódó ötletek vagy információs listák csoportjai. A szövegalakzatok magassága sorban csökken, az 1. szintű szöveg függőlegesen jelenik meg. |
| DescendingProcess | `46` | Lejjebb haladó eseménysorozat. Az első 1. szintű szöveg a nyíl tetején, az utolsó 1. szintű szöveg a nyíl alján jelenik meg. Csak az első hét 1. szintű elem jelenik meg. Leginkább kis-közepes mennyiségű szöveggel a legjobb. |
| DetailedProcess | `47` | Nagy mennyiségű 2. szintű szöveggel a folyamat fokozatos szakaszokra bontásához. |
| DivergingArrows | `48` | Ötletek vagy koncepciók, amelyek egy központi forrástól távolodnak. Leginkább csak 1. szintű szöveggel a legjobb. |
| DivergingRadial | `49` | Kapcsolat központi ötlethez egy körkörös áramlásban. Az első 1. szintű szövegsor a központi kör alakzatnak felel meg. Hangsúlyozza a körülötte lévő köröket a központi ötlet helyett. A nem használt szöveg nem jelenik meg, de elérhető, ha az elrendezést módosítja. |
| Equation | `50` | Szekvenciális lépések vagy feladatok, amelyek egy tervet vagy eredményt ábrázolnak. Az utolsó 1. szintű szöveg a egyenlőségjel (=) után jelenik meg. Leginkább csak 1. szintű szöveggel a legjobb. |
| FramedTextPicture | `51` | Képek a megfelelő 1. szintű szöveggel, amely keretben jelenik meg. |
| Funnel | `52` | Információ szűrésének vagy a részek egy egésszé összeolvadásának bemutatása. Hangsúlyozza a végső eredményt. Legfeljebb négy 1. szintű szövegsor tárolható; az utolsó sor a tölcsér alatt, a többi sor egy kör alakzatnak felel meg. A nem használt szöveg nem jelenik meg, de elérhető, ha az elrendezést módosítja. |
| Gear | `53` | Összefonódó ötletek. Az 1. szintű szöveg első három sora egy fogaskerék alakzatnak, a megfelelő 2. szintű szöveg pedig a fogaskerék mellé tartozó téglalapokban jelenik meg. A nem használt szöveg nem jelenik meg, de elérhető, ha az elrendezést módosítja. |
| GridMatrix | `54` | Koncepciók elhelyezése két tengely mentén. Hangsúlyozza az egyes összetevőket az egész helyett. Az 1. szintű szöveg első négy sora a kvadránsokban jelenik meg. A nem használt szöveg nem jelenik meg, de elérhető, ha az elrendezést módosítja. |
| GroupedList | `55` | Információcsoportok és alkategóriák, vagy feladat, folyamat, munkafolyamat lépései és allépései. Az 1. szintű szöveg a felső vízszintes alakzatoknak, a 2. szintű szöveg a kapcsolódó felső szintű alakzatok alatti függőleges allépéseknek felel meg. Jól használható al-csoportok vagy al-lépések, hierarchikus információk vagy több információs lista hangsúlyozására. |
| HalfCircleOrganizationChart | `56` | Hierarchikus információ vagy szervezeti jelentési kapcsolatok. A segítő alakzatok és az Org Chart függőleges elrendezés ebben az elrendezésben érhető el. |
| HexagonCluster | `57` | Képek a hozzájuk tartozó leíró szöveggel. A kis hatszögek a kép-szöveg párost jelzik. Leginkább kis mennyiségű szöveggel a legjobb. |
| Hierarchy | `58` | Hierarchikus kapcsolatok, amelyek felülről lefele haladnak. |
| HierarchyList | `59` | Hierarchikus kapcsolatok csoportokban. Használható információk csoportosítására vagy listázására is. |
| HorizontalBulletList | `60` | Nem szekvenciális vagy csoportosított információs listák. Nagy mennyiségű szöveghez alkalmas. Minden szöveg azonos hangsúlyú, irány nem feltétlenül értelmezhető. |
| HorizontalHierarchy | `61` | Hierarchikus kapcsolatok vízszintes irányban. Döntési fákhoz alkalmas. |
| HorizontalLabeledHierarchy | `62` | Hierarchikus kapcsolatok vízszintes és csoportosított hierarchiában. Hangsúlyozza a címsor vagy 1. szintű szöveget. Az 1. szintű szöveg első sora a hierarchia kezdeti alakzatban jelenik meg, a második és az azt követő sorok a magas téglalapok tetején. |
| HorizontalMultiLevelHierarchy | `63` | Nagy mennyiségű hierarchikus információ vízszintes irányban. A hierarchia teteje függőlegesen jelenik meg. Ez az elrendezés sok szintet támogat. |
| HorizontalOrganizationChart | `64` | Hierarchikus információ vagy szervezeti jelentési kapcsolatok vízszintesen. A segítő alakzat és az Org Chart függőleges elrendezés ebben az elrendezésben érhető el. |
| HorizontalPictureList | `65` | Nem szekvenciális vagy csoportosított információ, hangsúly a kapcsolódó képeken. A felső alakzatok képek tárolására szolgálnak. |
| IncreasingArrowsProcess | `66` | Szekvenciális és átfedő lépések egy folyamatban. Legfeljebb öt 1. szintű elem. A 2. szintű szöveg nagy mennyiségű lehet. |
| IncreasingCircleProcess | `67` | Lépések sorozata, ahol a kör belseje növekszik minden lépéssel. Legfeljebb hét 1. szintű lépés, a 2. szintű elemek korlátlanok. Nagy mennyiségű 2. szintű szöveggel a legjobb. |
| InvertedPyramid | `68` | Arányos, összefüggő vagy hierarchikus kapcsolatok, a legnagyobb komponens felül, szűkülve lefelé. Az 1. szintű szöveg a piramis szegmenseiben, a 2. szintű szöveg a szegmensek melletti alakzatokban jelenik meg. |
| LabeledHierarchy | `69` | Hierarchikus kapcsolatok felülről lefele, csoportosított hierarchiában. Hangsúlyozza a címsort vagy 1. szintű szöveget. Az 1. szintű szöveg első sora a hierarchia kezdő alakzatában, a további sorok a hosszú téglalapok bal oldalán jelennek meg. |
| LinearVenn | `70` | Átfedő kapcsolatok sorozatban. Leginkább csak 1. szintű szöveggel a legjobb. |
| LinedList | `71` | Nagy mennyiségű szöveg kategóriákra és alkategóriákra osztva. Több szintű szöveghez alkalmas. Azonos szintű szöveg vonalakkal van elválasztva. |
| MultidirectionalCycle | `72` | A szakaszok, feladatok vagy események folyamatos sorozata, amely bármilyen irányban előfordulhat. |
| NameandTitleOrganizationChart | `73` | Hierarchikus információ vagy szervezeti jelentési kapcsolatok. A cím dobozba való szövegbevitelhez írjon közvetlenül a kisebb téglalap alakzatba. A segítő alakzat és az Org Chart függőleges elrendezés ebben az elrendezésben érhető el. |
| NestedTarget | `74` | Tartalmazási kapcsolatok. Az 1. szintű szöveg első három sora a bal felső szöveget a alakzatokban, a 2. szintű szöveg a kisebb alakzatokban jelenik meg. Leginkább minimális 2. szintű szövegsorokkal a legjobb. A nem használt szöveg nem jelenik meg, de elérhető, ha az elrendezést módosítja. |
| NondirectionalCycle | `75` | A szakaszok, feladatok vagy események folyamatos körkörös sorozata. Minden alakzat azonos súlyú. Akkor a legjobb, ha nincs szükség irány jelzésére. |
| OpposingArrows | `76` | Két ellentétes ötlet vagy koncepció, amelyek egy központi pontból származnak. Az 1. szintű szöveg első két sora egy nyílnak felel meg. A nem használt szöveg nem jelenik meg, de elérhető, ha az elrendezést módosítja. |
| OpposingIdeas | `77` | Két ellentétes vagy kontrasztos ötlet. Lehet egy vagy két 1. szintű elem. Minden 1. szintű szöveg több al-szintet tartalmazhat. Nagy mennyiségű szöveghez alkalmas. |
| OrganizationChart | `78` | Hierarchikus információ vagy szervezeti jelentési kapcsolatok. A segítő alakzat és az Org Chart függőleges elrendezés ebben az elrendezésben érhető el. |
| PhasedProcess | `79` | Három fázisú folyamat. Legfeljebb három 1. szintű elem. Az első két 1. szintű elem négy 2. szintű elemet tartalmazhat, a harmadik 1. szintű elem korlátlan számú 2. szintű elemet. Leginkább kis mennyiségű szöveggel a legjobb. |
| PictureAccentBlocks | `80` | Képek csoportja blokkokban a saroktól indulva. A megfelelő szöveg függőlegesen jelenik meg. Jól használható címlapok vagy al-címek diáinak hangsúlyozásához vagy dokumentum szakaszok elválasztásához. |
| PictureAccentList | `81` | Csoportos vagy kapcsolódó információ. A felső sarkok kis alakzatai képek tárolására szolgálnak. Hangsúlyozza a 2. szintű szöveget az 1. szintű felett, nagy mennyiségű 2. szintű szöveghez jó választás. |
| PictureAccentProcess | `82` | Szekvenciális lépések feladat, folyamat, munkafolyamat. A háttér téglalap alakzatok képek tárolására szolgálnak. |
| PictureCaptionList | `83` | Nem szekvenciális vagy csoportosított információs blokkok. A felső alakzatok képek tárolására szolgálnak, a képek a szöveg felett vannak hangsúlyozva. Képek rövid felirattal jól működnek. |
| PictureGrid | `84` | Képek négyzetes rácson. Leginkább kis mennyiségű 1. szintű szöveg, amely a kép felett jelenik meg. |
| PictureLineup | `85` | Képsorozat egymás mellett. Az 1. szintű szöveg a kép tetejét fedi. A 2. szintű szöveg a kép alatt jelenik meg. |
| PictureStrips | `86` | Képsorozat felülről lefelé, 1. szintű szöveg mindegyik mellett. |
| PieProcess | `87` | Lépések egy folyamatban, minden szelet egyre nagyobb, legfeljebb hét alakzat. Az 1. szintű szöveg függőlegesen jelenik meg. |
| PlusandMinus | `88` | Két ötlet előnyei és hátrányai. Minden 1. szintű szöveg több al-szintet tartalmazhat. Nagy mennyiségű szöveghez alkalmas. Legfeljebb két 1. szintű elem. |
| ProcessArrows | `89` | Információ illusztrálja a folyamatot vagy munkafolyamatot. Az 1. szintű szöveg kör alakzatokban, a 2. szintű szöveg nyíl alakzatokban jelenik meg. Leginkább minimális szöveggel, a mozgás vagy irány hangsúlyozásához. |
| ProcessList | `90` | Több információs csoport vagy lépés és al-lépés feladat, folyamat, munkafolyamat. Az 1. szintű szöveg a felső vízszintes alakzatoknak, a 2. szintű szöveg a kapcsolódó felső alakzatok alatti függőleges allépéseknek felel meg. |
| PyramidList | `91` | Arányos, összefüggő vagy hierarchikus kapcsolatok. A szöveg a piramis háttérre helyezett téglalap alakzatokban jelenik meg. |
| RadialCluster | `92` | Adatok, amelyek egy központi ötlethez vagy témához kapcsolódnak. Az 1. szintű szöveg a tetején a központban. A 2. szintű szöveg körülvevő alakzatokban. Legfeljebb hét 2. szintű alakzat tárolható. A nem használt szöveg nem jelenik meg, de elérhető, ha az elrendezést módosítja. Leginkább kis mennyiségű szöveggel a legjobb. |
| RadialCycle | `93` | Kapcsolat központi ötlethez. Hangsúlyozza a központi körben lévő információt és a körök külső gyűrűjének hozzájárulását a központi ötlethez. Az 1. szintű szöveg első sora a központi körnek, a 2. szintű szöveg a külső köröknek. A nem használt szöveg nem jelenik meg, de elérhető, ha az elrendezést módosítja. |
| RadialList | `94` | Kapcsolatok központi ötlethez egy körkörös áramlásban. A középső alakzat képet tartalmazhat. Az 1. szintű szöveg a kisebb körökben, a kapcsolódó 2. szintű szöveg a kisebb körök melletti oldalon jelenik meg. |
| RadialVenn | `95` | Átfedő kapcsolatok és a központi ötlethez való kapcsolat egy körkörös áramlásban. Az 1. szintű szöveg első sora a központi alakzatnak, a 2. szintű szöveg sorai a körülötte lévő kör alakzatoknak. A nem használt szöveg nem jelenik meg, de elérhető, ha az elrendezést módosítja. |
| RandomToResultProcess | `96` | Lépéseken keresztül megmutatja, hogyan eredhetnek kaotikus ötletek egységes célból. Több 1. szintű szöveg is támogatott, de az első és utolsó 1. szintű alakzat rögzített. Leginkább kis mennyiségű 1. szintű és közepes 2. szintű szöveggel a legjobb. |
| RepeatingBendingProcess | `97` | Folyamat vagy szekvenciális lépések feladat, folyamat, munkafolyamat. Maximalizálja a vízszintes és függőleges helyet az alakzatok számára. |
| ReverseList | `98` | Két elem közti váltás. Csak az első két szövegsor jelenik meg, minden elem nagy mennyiségű szöveget tartalmazhat. Jó a két elem közti változás vagy sorrend áthelyezésére. |
| SegmentedCycle | `99` | Folyamat vagy szakaszok, feladatok vagy események sorozata körkörös áramlásban. Hangsúlyozza az összefüggő elemeket. Az 1. szintű szöveg első hét sora egy szelet vagy kör alakzatnak felel meg. A nem használt szöveg nem jelenik meg, de elérhető, ha az elrendezést módosítja. |
| SegmentedProcess | `100` | Folyamat vagy szekvenciális lépések feladat, folyamat, munkafolyamat. Hangsúlyozza a 2. szintű szöveget, mivel minden sor külön alakzatban jelenik meg. |
| SegmentedPyramid | `101` | Tartalmazás, arányos vagy összefüggő kapcsolatok. Az 1. szintű szöveg első kilenc sora háromszög alakzatokban jelenik meg. A nem használt szöveg nem jelenik meg, de elérhető, ha az elrendezést módosítja. Leginkább csak 1. szintű szöveggel a legjobb. |
| SnapshotPictureList | `102` | Képek magyarázó szöveggel. A 2. szintű szöveg információlistákat jeleníthet meg. Nagy mennyiségű szöveghez alkalmas. |
| SpiralPicture | `103` | Legfeljebb öt kép sorozata, a megfelelő 1. szintű feliratok spirálisan a középpont felé haladva. |
| SquareAccentList | `104` | Információlisták kategóriákra osztva. A 2. szintű szöveg egy kis négyzet alakzat mellett jelenik meg. Nagy mennyiségű 2. szintű szöveghez jó. |
| StackedList | `105` | Információcsoportok vagy lépések feladat, folyamat, munkafolyamat. Kör alakzatok 1. szintű szöveget tartalmaznak, a megfelelő téglalapok 2. szintű szöveget. Sok részlet és minimális 1. szintű szöveg esetén alkalmas. |
| StackedVenn | `106` | Átfedő kapcsolatok. Jó választás a növekedés vagy fokozat hangsúlyozására. Leginkább csak 1. szintű szöveggel a legjobb. Az első hét 1. szintű sor egy kör alakzatnak felel meg. A nem használt szöveg nem jelenik meg, de elérhető, ha az elrendezést módosítja. |
| StaggeredProcess | `107` | Lefelé haladó folyamat szakaszok szerint. Az első öt 1. szintű sor egy téglalapnak felel meg. A nem használt szöveg nem jelenik meg, de elérhető, ha az elrendezést módosítja. |
| StepDownProcess | `108` | Lejjebb haladó folyamat több lépéssel és al-lépéssel. Leginkább kis mennyiségű szöveggel a legjobb. |
| StepUpProcess | `109` | Felfelé haladó lépéssorozat vagy információlista. |
| SubStepProcess | `110` | Többlépéses folyamat al-lépésekkel minden 1. szintű szöveg között. Leginkább kis mennyiségű szöveggel, legfeljebb hét 1. szintű lépés. Minden 1. szintű lépésnek korlátlan al-lépése lehet. |
| TableHierarchy | `111` | Információcsoportok felülről lefele, és a hierarchiák minden csoportban. Ez az elrendezés nem tartalmaz összekötő vonalakat. |
| TableList | `112` | Csoportos vagy kapcsolódó információ egyenlő értékkel. Az első 1. szintű sor a felső alakzatnak felel meg, a 2. szintű szöveg a követő listákhoz használható. |
| TargetList | `113` | Összefüggő vagy átfedő információ. Az első hét 1. szintű sor a téglalap alakzatban jelenik meg. A nem használt szöveg nem jelenik meg, de elérhető, ha az elrendezést módosítja. Mind az 1., mind a 2. szintű szöveg jól működik. |
| TextCycle | `114` | A szakaszok, feladatok vagy események folyamatos körkörös sorozata. Hangsúlyozza a nyilakat vagy áramlást a szakaszok vagy lépések helyett. Leginkább csak 1. szintű szöveggel a legjobb. |
| TitlePictureLineup | `115` | Képsorozat, mindegyik saját címmel és leírással. Az 1. szintű szöveg a kép fölötti dobozban jelenik meg. A 2. szintű szöveg a kép alatt jelenik meg. |
| TitledMatrix | `116` | Négy kvadráns és az egészen belüli kapcsolat. Az 1. szintű szöveg első sora a központi alakzatnak, a 2. szintű szöveg első négy sora a kvadránsokban. A nem használt szöveg nem jelenik meg, de elérhető, ha az elrendezést módosítja. |
| TitledPictureAccentList | `117` | Információlisták, minden 2. szintű szöveghez egy hangsúlyos kép. Az 1. szintű szöveg egy külön dobozban a lista tetején jelenik meg. |
| TitledPictureBlocks | `118` | Képsorozat. Az 1. szintű szöveg minden kép fölött jelenik meg. A 2. szintű szöveg a kép oldalán, kissé átfedve jelenik meg. |
| TrapezoidList | `119` | Csoportos vagy kapcsolódó információ egyenlő értékkel. Nagy mennyiségű szöveghez alkalmas. |
| UpwardArrow | `120` | Folyamat vagy lépések, amelyek felfelé ívelnek feladat, folyamat vagy munkafolyamat során. Az 1. szintű szöveg első öt sora az nyíl egy pontjának felel meg. Leginkább minimális szöveggel a legjobb. A nem használt szöveg nem jelenik meg, de elérhető, ha az elrendezést módosítja. |
| VerticalAccentList | `121` | Információlisták. A 2. szintű szöveg téglalap alakzatokban, függőleges cikkcakkok felett jelenik meg. Hangsúlyozza a 2. szintű szöveget az 1. szintű helyett, közepes mennyiségű 2. szintű szöveghez jó választás. |
| VerticalArrowList | `122` | Folyamat vagy szekvenciális lépések feladat, folyamat, munkafolyamat, amely közös cél felé halad. Jól használható felsorolásokhoz. |
| VerticalBendingProcess | `123` | Folyamat vagy szekvenciális lépések feladat, folyamat, munkafolyamat. Maximalizálja a vízszintes és függőleges helyet az alakzatok számára. Több hangsúlyt fektet az alakzatok közti kapcsolatra, mint az irányra vagy mozgásra. |
| VerticalBlockList | `124` | Információcsoportok vagy lépések feladat, folyamat, munkafolyamat. Nagy mennyiségű 2. szintű szöveghez alkalmas. Jó választás fő pont és több al-pont kombinációjára. |
| VerticalBoxList | `125` | Több információcsoport, különösen nagy mennyiségű 2. szintű szöveggel. Jó választás felsorolásokhoz. |
| VerticalBulletList | `126` | Nem szekvenciális vagy csoportosított információs blokkok. Hosszú címsorok vagy felső szintű információk listáihoz alkalmas. |
| VerticalChevronList | `127` | Folyamat vagy szekvenciális lépések feladat, folyamat, munkafolyamat, vagy a mozgás/irány hangsúlyozása. Hangsúlyozza a 2. szintű szöveget az 1. szintű helyett, nagy mennyiségű 2. szintű szöveghez jó választás. |
| VerticalCircleList | `128` | Szekvenciális vagy csoportosított adatok. Leginkább 1. szintű szöveg, amely egy nagy kör alakzat mellett jelenik meg. Az alacsonyabb szövegszintek kisebb körökkel vannak elválasztva. |
| VerticalCurvedList | `129` | Görbe lista információkkal. Kerekített kör alakzatokhoz képet kell alkalmazni a kitöltéshez. |
| VerticalEquation | `130` | Szekvenciális lépések vagy feladatok, amelyek egy tervet vagy eredményt ábrázolnak. Az utolsó 1. szintű sor a nyíl után jelenik meg. Leginkább csak 1. szintű szöveggel a legjobb. |
| VerticalPictureAccentList | `131` | Nem szekvenciális vagy csoportosított információs blokkok. A kis körök képek tárolására vannak tervezve. |
| VerticalPictureList | `132` | Nem szekvenciális vagy csoportosított információk. A bal oldali kis alakzatok képek tárolására szolgálnak. |
| VerticalProcess | `133` | Folyamat vagy szekvenciális lépések feladat, folyamat, munkafolyamat felülről lefelé. Leginkább 1. szintű szöveggel a legjobb, mivel a függőleges tér korlátozott. |
| Custom | `134` | Egy saját elrendezésű SmartArt diagramot képvisel |
| PictureOrganizationChart | `135` | Hierarchikus információ vagy szervezeti jelentési kapcsolatok, képekhez tartozóan. A segítő alakzat és az Org Chart függőleges elrendezés ebben az elrendezésben érhető el. |

### Lásd még

* névtér [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->