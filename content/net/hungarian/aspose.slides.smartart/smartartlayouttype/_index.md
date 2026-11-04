---
title: SmartArtLayoutType
second_title: Aspose.Sildes .NET API-referencia
description: A SmartArt diagram elrendezés típusát képviseli.
type: docs
weight: 10640
url: /hu/aspose.slides.smartart/smartartlayouttype/
---
## SmartArtLayoutType enumeráció

A SmartArt diagram elrendezéstípusát képviseli.

```csharp
public enum SmartArtLayoutType
```

### Values

| Név | Érték | Leírás |
| --- | --- | --- |
| AccentProcess | `0` | Használja előrehaladás, idővonal vagy egy feladat, folyamat vagy munkafolyamat szekvenciális lépéseinek megjelenítéséhez. Jól működik a Level 1 és Level 2 szöveg illusztrálására. |
| AccentedPicture | `1` | Használja központi, fotó alapú ötlet megjelenítésére, a kapcsolódó ötletekkel a szélén. A felső Level 1 szöveg a központi képen jelenik meg. A többi Level 1 alakhoz tartozó szöveg a kis kör alakú képek mellett jelenik meg. Ez az elrendezés szöveg nélkül is jól működik. |
| AlternatingFlow | `2` | Használja információcsoportok vagy egy feladat, folyamat vagy munkafolyamat szekvenciális lépéseinek megjelenítésére. Kiemeli az információcsoportok közti interakciót vagy kapcsolatot. |
| AlternatingHexagons | `3` | Használja összefüggő ötletek sorozatának ábrázolására. A Level 1 szöveg a hatszögeken belül jelenik meg. A Level 2 szöveg a formák kívül. |
| AlternatingPictureBlocks | `4` | Használja egy sor képet felülről lefelé megjelenítésére. A szöveg váltakozva a kép jobb vagy bal oldalán jelenik meg. |
| AlternatingPictureCircles | `5` | Használja képek és szöveg készletének megjelenítésére. A megfelelő szöveg a középső körökben jelenik meg, a képek balról jobbra váltakoznak. |
| ArrowRibbon | `6` | Használja kapcsolódó vagy ellentétes fogalmak megjelenítésére némi kapcsolattal, például ellenkező erőket. A Level 1 szöveg első két sorát használják a nyilak szövegéhez. A fel nem használt szöveg nem jelenik meg, de elérhető marad, ha elrendezést vált. |
| AscendingPictureAccentProcess | `7` | Használja emelkedő sorozatú képek és leíró szöveg megjelenítésére. Leginkább kevés szöveggel működik. |
| Balance | `8` | Használja két ötlet összehasonlítására vagy kapcsolatuk megjelenítésére. A Level 1 szöveg első két sora a középpont egyik oldalának tetején lévő szövegnek felel meg. Kiemeli a Level 2 szöveget, amely legfeljebb négy alakra korlátozódik a középpont mindkét oldalán. A mérleg a legtöbb Level 2 szöveget tartalmazó oldal felé billen. A fel nem használt szöveg nem jelenik meg, de elérhető marad, ha elrendezést vált. |
| BasicBendingProcess | `9` | Használja egy feladat, folyamat vagy munkafolyamat előrehaladás vagy szekvenciális lépéseinek megjelenítésére. A formák vízszintes és függőleges megjelenítési helyét maximalizálja. |
| BasicBlockList | `10` | Használja nem szekvenciális vagy csoportos információs blokkok megjelenítésére. A formák vízszintes és függőleges helyét maximalizálja. |
| BasicChevronProcess | `11` | Használja előrehaladást, idővonalat, szekvenciális lépéseket vagy a mozgás vagy irány kiemelésére. A Level 1 szöveg egy nyíl alakzat belsejében, a Level 2 szöveg a nyíl alakzatok alatt jelenik meg. |
| BasicCycle | `12` | Használja egy körkörös áramlásban lévő szakaszok, feladatok vagy események folyamatos sorozatának ábrázolására. A szakaszokat vagy lépéseket emeli ki a csatlakozó nyilak vagy áramlás helyett. Leginkább csak Level 1 szöveggel működik. |
| BasicMatrix | `13` | Használja összetevők és egész közötti kapcsolat megjelenítésére kvadránsokban. A Level 1 szöveg első négy sora a kvadránsokban jelenik meg. A fel nem használt szöveg nem jelenik meg, de elérhető marad, ha elrendezést vált. |
| BasicPie | `14` | Használja, hogyan alkotnak az egyes részek egészet. A Level 1 szöveg első hét sora megfelel egyenletesen elosztott szelet vagy kör alakzatoknak. A felső Level 1 szöveg alakzat a kör többi részétől kívül jelenik meg a hangsúlyozás érdekében. A fel nem használt szöveg nem jelenik meg, de elérhető marad, ha elrendezést vált. |
| BasicProcess | `15` | Használja egy feladat, folyamat vagy munkafolyamat előrehaladás vagy szekvenciális lépéseinek megjelenítésére. |
| BasicPyramid | `16` | Használja arányos, összefüggő vagy hierarchikus kapcsolatok megjelenítésére, a legnagyobb összetevő alul, szűkülve felfelé. A Level 1 szöveg a piramis szegmenseiben, a Level 2 szöveg a szegmensek mellett lévő alakzatokban jelenik meg. |
| BasicRadial | `17` | Használja központi ötlethez kapcsolódó kapcsolat megjelenítésére egy ciklusban. A Level 1 szöveg első sora a központi alakzathoz tartozik, a Level 2 szöveg a körülöttük lévő kör alakzatokhoz. |
| BasicTarget | `18` | Használja tartalmazást, fokozatokat vagy hierarchikus kapcsolatok megjelenítésére. A Level 1 szöveg első öt sora egy körhez kapcsolódik. A fel nem használt szöveg nem jelenik meg, de elérhető marad, ha elrendezést vált. |
| BasicTimeline | `19` | Használja szekvenciális lépések megjelenítésére egy feladat, folyamat vagy munkafolyamat során, vagy idővonal információk megjelenítésére. Mind a Level 1, mind a Level 2 szöveg jól működik. |
| BasicVenn | `20` | Használja átfedő vagy összefüggő kapcsolatok megjelenítésére. A Level 1 szöveg első hét sora egy körrel egyezik. Ha négy vagy kevesebb sor van, a szöveg a körök belsejében van. Ha több mint négy sor, a szöveg a körök kívül van. A fel nem használt szöveg nem jelenik meg, de elérhető marad, ha elrendezést vált. |
| BendingPictureAccentList | `21` | Használja nem szekvenciális vagy csoportos információs blokkok megjelenítésére. A kis kör alakzatok képek tárolására vannak tervezve. Jól működik mind Level 1, mind Level 2 szöveg illusztrálására. A formák vízszintes és függőleges helyét maximalizálja. |
| BendingPictureBlocks | `22` | Használja egy sor képet megjelenítésére. Az alulra eső doboz kis mennyiségű szöveget tartalmazhat. |
| BendingPictureCaption | `23` | Használja egymást követő képsorozat megjelenítésére. Az alulra eső doboz kis mennyiségű szöveget tartalmazhat. |
| BendingPictureCaptionList | `24` | Használja egy sor képet megjelenítésére. A cím és leírás felhívó alakzatban jelenik meg minden kép alatt. |
| BendingPictureSemiTransparentText | `25` | Használja egy sor képet megjelenítésére. Egy félig átlátszó doboz fedi a kép alsó részét és tartalmazza az összes szint szövegét. |
| BlockCycle | `26` | Használja egy körkörös áramlásban lévő szakaszok, feladatok vagy események folyamatos sorozatának ábrázolására. A szakaszokat vagy lépéseket emeli ki a csatlakozó nyilak vagy áramlás helyett. |
| BubblePictureList | `27` | Használja egy sor képet megjelenítésére. Legfeljebb nyolc Level 1 képet tartalmazhat. A fel nem használt szöveg és képek nem jelennek meg, de elérhetők, ha elrendezést vált. Leginkább kis mennyiségű szöveggel működik. |
| CaptionedPictures | `28` | Használja képeket több szintű szöveggel. Leginkább kis mennyiségű Level 1 szöveg és közepes mennyiségű Level 2 szöveg mellett működik. |
| ChevronList | `29` | Használja előrehaladást több folyamaton keresztül, amelyek egy összefüggő munkafolyamatot alkotnak. Jól használható ellentétes folyamatok illusztrálására is. A Level 1 szöveg a bal oldali első nyíl alakzathoz tartozik, míg a Level 2 szöveg a Level 1 szöveget tartalmazó alakzatokhoz tartozó vízszintes al-lépéseket jelöli. |
| CircleAccentTimeline | `30` | Használja események vagy idővonal információk sorozatának megjelenítésére. A Level 1 szöveg a nagyobb kör alakzatok mellett jelenik meg. A Level 2 szöveg a kisebb kör alakzatok mellett. |
| CircleArrowProcess | `31` | Használja szekvenciális elemeket, mindegyikhez tartozó támogatási szöveggel. Ez a diagram leginkább kis mennyiségű Level 1 szöveggel működik. |
| CirclePictureHierarchy | `32` | Használja hierarchikus információk vagy szervezeti jelentési kapcsolatok megjelenítésére. A képek körökben jelennek meg és a megfelelő szöveg a képek mellett. |
| CircleRelationship | `33` | Használja a kapcsolatot egy központi ötlethez vagy onnan. A Level 2 szöveg nem szekvenciálisan kerül hozzá és legfeljebb öt elemet tartalmaz. Csak egy Level 1 elem lehet. |
| CircularBendingProcess | `34` | Használja hosszú vagy nem lineáris sorozatot vagy lépéseket egy feladat, folyamat vagy munkafolyamat során. Leginkább csak Level 1 szöveggel működik. A formák vízszintes és függőleges helyét maximalizálja. |
| CircularPictureCallout | `35` | Használja egy központi ötlet és alötletek vagy kapcsolódó elemek megjelenítésére. Az első kép szövege a kép alsó részét fedi. A többi Level 1 alakzathoz tartozó szöveg a kis kör alakú képek mellett jelenik meg. Ez a diagram szöveg nélkül is jól működik. |
| ClosedChevronProcess | `36` | Használja előrehaladást, idővonalát vagy szekvenciális lépéseket egy feladat, folyamat vagy munkafolyamat során, vagy a mozgás vagy irány kiemelésére. Használható a kiinduló alakzat információjának kiemelésére. Leginkább csak Level 1 szöveggel működik. |
| ContinuousArrowProcess | `37` | Használja idővonalat vagy szekvenciális lépéseket egy feladat, folyamat vagy munkafolyamat során. Leginkább Level 1 szöveggel, mivel minden Level 1 szövegsor a nyíl alakzat belsejében jelenik meg. A Level 2 szöveg a nyíl alakzat kívül. |
| ContinuousBlockProcess | `38` | Használja előrehaladást vagy szekvenciális lépéseket egy feladat, folyamat vagy munkafolyamat során. Leginkább minimális Level 1 és Level 2 szöveggel működik. |
| ContinuousCycle | `39` | Használja egy körkörös áramlásban lévő szakaszok, feladatok vagy események folyamatos sorozatának ábrázolására. Kiemeli az összetevők közti kapcsolatot. Leginkább csak Level 1 szöveggel. |
| ContinuousPictureList | `40` | Használja egymással összefüggő információcsoportok megjelenítésére. A kör alakzatok képek tárolására vannak tervezve. |
| ConvergingArrows | `41` | Használja ötletek vagy koncepciók ábrázolására, amelyek egy központi ponthoz konvergálnak. Leginkább csak Level 1 szöveggel. |
| ConvergingRadial | `42` | Használja koncepciók vagy összetevők kapcsolatait egy központi ötlethez egy ciklusban. A Level 1 szöveg első sora a központi kör alakzathoz tartozik, a Level 2 szöveg sorai a körülöttük lévő téglalap alakzatokhoz. A fel nem használt szöveg nem jelenik meg, de elérhető marad, ha elrendezést vált. |
| CounterbalanceArrows | `43` | Használja két ellentétes ötlet vagy koncepció ábrázolására. A Level 1 szöveg első két sora egy nyílhoz tartozik és jól működik Level 2 szöveggel. A fel nem használt szöveg nem jelenik meg, de elérhető marad, ha elrendezést vált. |
| CycleMatrix | `44` | Használja a kapcsolatot egy központi ötlethez egy ciklikus előrehaladásban. A Level 1 szöveg első négy sora egy szelet vagy kör alakzathoz tartozik, a Level 2 szöveg egy téglalap alakzatban a szelet vagy kör alakzat oldalán jelenik meg. A fel nem használt szöveg nem jelenik meg, de elérhető marad, ha elrendezést vált. |
| DescendingBlockList | `45` | Használja kapcsolódó ötletek vagy információs listák csoportjait. A szöveg alakzatok magassága sorban csökken, a Level 1 szöveg függőlegesen jelenik meg. |
| DescendingProcess | `46` | Használja egy leereszkedő eseménysorozat megjelenítésére. Az első Level 1 szöveg a nyíl tetején, az utolsó Level 1 szöveg a nyíl alján jelenik meg. Csak az első hét Level 1 elem látható. Leginkább kis-közepes mennyiségű szöveggel működik. |
| DetailedProcess | `47` | Használja nagy mennyiségű Level 2 szöveggel a szakaszok közötti előrehaladás megjelenítésére. |
| DivergingArrows | `48` | Használja ötletek vagy koncepciók megjelenítésére, melyek kifelé haladnak egy központi forrásból. Leginkább csak Level 1 szöveggel. |
| DivergingRadial | `49` | Használja központi ötlethez tartozó kapcsolatok megjelenítésére egy ciklusban. A Level 1 szöveg első sora a központi kör alakzathoz tartozik. A körülötte lévő köröket emeli ki a központi ötlet helyett. A fel nem használt szöveg nem jelenik meg, de elérhető marad, ha elrendezést vált. |
| Equation | `50` | Használja szekvenciális lépések vagy feladatok ábrázolására, amelyek egy tervet vagy eredményt mutatnak. Az utolsó Level 1 szöveg az egyenlőségjel (=) után jelenik meg. Leginkább csak Level 1 szöveggel. |
| FramedTextPicture | `51` | Használja képek megjelenítésére, a megfelelő Level 1 szöveg keretben. |
| Funnel | `52` | Használja információ szűrésének vagy a részek egészbe egyesülésének megjelenítésére. Kiemeli a végső eredményt. Legfeljebb négy Level 1 szövegsor tartalmazható; az utolsó sor a szűkítő alján jelenik meg, a többi sor a kör alakzatokhoz kapcsolódik. A fel nem használt szöveg nem jelenik meg, de elérhető marad, ha elrendezést vált. |
| Gear | `53` | Használja az összekapcsolt ötletek megjelenítésére. A Level 1 szöveg első három sora egy-egy fogaskerék alaknak felel meg, és a hozzájuk tartozó Level 2 szöveg a fogaskerék alak mellett lévő téglalapokban jelenik meg. A fel nem használt szöveg nem jelenik meg, de elérhető marad, ha átvált a elrendezéseket. |
| GridMatrix | `54` | Használja a koncepciók két tengely menti elhelyezkedésének megjelenítésére. Az egyes komponensekre helyezi a hangsúlyt a teljes helyett. A Level 1 szöveg első négy sora a kvadránsokban jelenik meg. A fel nem használt szöveg nem jelenik meg, de elérhető marad, ha átvált a elrendezéseket. |
| GroupedList | `55` | Használja információcsoportok és al-csoportok, vagy feladat, folyamat vagy munkafolyamat lépéseinek és al-lépéseinek megjelenítésére. A Level 1 szöveg a felső szintű vízszintes alakzatoknak felel meg, a Level 2 szöveg pedig a kapcsolódó felső szintű alakzatok alatti függőleges al-lépéseknek. Jól használható az al-csoportok vagy al-lépések, hierarchikus információk, vagy több információlista hangsúlyozására. |
| HalfCircleOrganizationChart | `56` | Használja hierarchikus információ vagy jelentési kapcsolatok egy szervezetben történő megjelenítésére. A segédalakzatok és az Org Chart függőleges elrendezések elérhetőek ezzel az elrendezéssel. |
| HexagonCluster | `57` | Használja képekhez kapcsolódó leíró szöveg megjelenítésére. A kis hatoldalak jelzik a kép-szöveg párost. Legjobban kis mennyiségű szövegnél működik. |
| Hierarchy | `58` | Használja a hierarchikus kapcsolatok felülről lefelé történő ábrázolására. |
| HierarchyList | `59` | Használja a hierarchikus kapcsolatok csoportok között történő ábrázolására. Alkalmazható információ csoportosítására vagy listázására is. |
| HorizontalBulletList | `60` | Használja nem sorozatos vagy csoportosított információlisták megjelenítésére. Nagy mennyiségű szövegnél működik jól. Minden szöveg azonos hangsúlyt kap, és nincs irányjelzés. |
| HorizontalHierarchy | `61` | Használja a hierarchikus kapcsolatok vízszintes ábrázolására. Döntési fák esetén működik jól. |
| HorizontalLabeledHierarchy | `62` | Használja a hierarchikus kapcsolatok vízszintes ábrázolására, melyek hierarchikusan csoportosítottak. A címsor vagy a Level 1 szöveg kap hangsúlyt. A Level 1 szöveg első sora a hierarchia elején lévő alakzatban jelenik meg, a második és a további sorok a magas téglalapok tetején. |
| HorizontalMultiLevelHierarchy | `63` | Használja nagy mennyiségű hierarchikus információ vízszintes ábrázolására. A hierarchia csúcsa függőlegesen jelenik meg. Ez az elrendezés több szintet is támogat a hierarchiában. |
| HorizontalOrganizationChart | `64` | Használja hierarchikus információ vagy jelentési kapcsolatok vízszintes ábrázolására egy szervezetben. A segédalakzat és az Org Chart függőleges elrendezések elérhetők ezzel az elrendezéssel. |
| HorizontalPictureList | `65` | Használja nem sorozatos vagy csoportosított információ megjelenítésére, hangsúlyt fektetve a kapcsolódó képekre. A felső alakzatok képeket tartalmazásra vannak tervezve. |
| IncreasingArrowsProcess | `66` | Használja egy folyamat sorozatos és átfedő lépéseinek megjelenítésére. Legfeljebb öt Level 1 elem használható. A Level 2 sok szöveget tartalmazhat. |
| IncreasingCircleProcess | `67` | Használja egy sor lépés megjelenítésére, ahol a kör belseje minden lépéssel nő. Legfeljebb hét Level 1 lépés, de a Level 2 elemek száma korlátlan. Nagy mennyiségű Level 2 szövegnél működik jól. |
| InvertedPyramid | `68` | Használja arányos, összekapcsolt vagy hierarchikus kapcsolatok ábrázolására, a legnagyobb elem felül, szűkülve lent. A Level 1 szöveg a piramis szegmenseiben jelenik meg, a Level 2 szöveg pedig az egyes szegmensekhez tartozó alakzatokban. |
| LabeledHierarchy | `69` | Használja a hierarchikus kapcsolatok felülről lefelé, hierarchikusan csoportosított ábrázolására. A címsor vagy a Level 1 szöveg kap hangsúlyt. A Level 1 szöveg első sora a hierarchia elején lévő alakzatban jelenik meg, a többi sor a hosszú téglalapok bal oldalán. |
| LinearVenn | `70` | Használja átfedő kapcsolatok sorozatban történő megjelenítésére. Legjobban csak Level 1 szöveggel működik. |
| LinedList | `71` | Használja nagy mennyiségű szöveg kategóriákra és alkategóriákra osztott megjelenítésére. Többszintű szövegnél működik jól. Az azonos szintű szövegek vonalakkal vannak elválasztva. |
| MultidirectionalCycle | `72` | Használja a szakaszok, feladatok vagy események folyamatos sorozatának bármely irányban történő megjelenítésére. |
| NameandTitleOrganizationChart | `73` | Használja hierarchikus információ vagy jelentési kapcsolatok egy szervezetben történő megjelenítésére. A cím mezőbe való szöveg beviteléhez írjon közvetlenül a kisebb téglalap alakzatba. A segédalakzat és az Org Chart függőleges elrendezések elérhetők ezzel az elrendezéssel. |
| NestedTarget | `74` | Használja tartalmazási kapcsolatok megjelenítésére. A Level 1 szöveg első három sora a formák bal felső szövegének felel meg, a Level 2 szöveg a kisebb alakzatokban jelenik meg. Legjobban minimális Level 2 soroknál működik. A fel nem használt szöveg nem jelenik meg, de elérhető marad, ha átvált a elrendezéseket. |
| NondirectionalCycle | `75` | Használja a szakaszok, feladatok vagy események körkörös folyamatos sorozatának ábrázolására. Minden alakzat azonos fontosságú. Jól használható, ha nincs szükség irány jelzésére. |
| OpposingArrows | `76` | Használja két ellentétes ötlet, vagy középponttól elágazó ötlet megjelenítésére. A Level 1 szöveg első két sora egy-egy nyílnak felel meg. A fel nem használt szöveg nem jelenik meg, de elérhető marad, ha átvált a elrendezéseket. |
| OpposingIdeas | `77` | Használja két ellentétes vagy kontrasztos ötlet megjelenítésére. Lehet egy vagy két Level 1 elem. Minden Level 1 szöveg több al-szintet is tartalmazhat. Nagy mennyiségű szövegnél működik jól. |
| OrganizationChart | `78` | Használja hierarchikus információ vagy jelentési kapcsolatok egy szervezetben történő megjelenítésére. A segédalakzat és az Org Chart függőleges elrendezések elérhetők ezzel az elrendezéssel. |
| PhasedProcess | `79` | Használja egy folyamat három fázisának megjelenítésére. Legfeljebb három Level 1 elem használható. Az első két Level 1 elem négy Level 2 elemet tartalmazhat, a harmadik Level 1 elem korlátlan számú Level 2 elemet tartalmazhat. Legjobban kis mennyiségű szövegnél működik. |
| PictureAccentBlocks | `80` | Használja képcsoport blokkokban, a saroktól indulva, megjelenítésére. A hozzá tartozó szöveg függőlegesen jelenik meg. Jó kiemelésként szolgál cím vagy alcím diákon, illetve dokumentum szakaszszéleknél. |
| PictureAccentList | `81` | Használja csoportos vagy kapcsolódó információ megjelenítésére. A felső sarkokban lévő kis alakzatok képek tartására lettek tervezve. A Level 2 szöveg kap hangsúlyt a Level 1 szöveggel szemben, és jó választás nagy mennyiségű Level 2 szöveghez. |
| PictureAccentProcess | `82` | Használja sorozatos lépések megjelenítésére egy feladat, folyamat vagy munkafolyamat során. A háttérben lévő téglalap alakzatok képek tartására vannak tervezve. |
| PictureCaptionList | `83` | Használja nem sorozatos vagy csoportosított információs blokkok megjelenítésére. A felső alakzatok képek tartására vannak tervezve, és a képek a szöveggel szemben hangsúlyt kapnak. Jól működik rövid feliratú képek esetén. |
| PictureGrid | `84` | Használja képek négyzetes rácsban történő elrendezésére. Legjobb kis mennyiségű Level 1 szöveggel, amely a kép felett jelenik meg. |
| PictureLineup | `85` | Használja egymás mellett elhelyezett képsorozat megjelenítésére. A Level 1 szöveg a kép tetejét fedi. A Level 2 szöveg a kép alatt jelenik meg. |
| PictureStrips | `86` | Használja a képek felülről lefelé sorozatának megjelenítésére, a Level 1 szöveggel minden kép mellett. |
| PieProcess | `87` | Használja egy folyamat lépéseinek megjelenítésére, ahol minden tortaszelet nagyobb lesz, legfeljebb hét alakzatig. A Level 1 szöveg függőlegesen jelenik meg. |
| PlusandMinus | `88` | Használja két ötlet előnyei és hátrányai megjelenítésére. Minden Level 1 szöveg több al-szintet tartalmazhat. Nagy mennyiségű szövegnél működik jól. Legfeljebb két Level 1 elem. |
| ProcessArrows | `89` | Használja egy folyamat vagy munkafolyamat illusztráló információ megjelenítésére. A Level 1 szöveg a kör alakzatokban, a Level 2 szöveg a nyíl alakzatokban jelenik meg. Legjobban minimális szövegnél, a mozgás vagy irány hangsúlyozására. |
| ProcessList | `90` | Használja több információcsoport vagy lépés és al-lépés feladat, folyamat vagy munkafolyamat során történő megjelenítésére. A Level 1 szöveg a felső vízszintes alakzatoknak felel meg, a Level 2 szöveg a kapcsolódó felső szintű alakzatok alatti függőleges al-lépéseknél. |
| PyramidList | `91` | Használja arányos, összekapcsolt vagy hierarchikus kapcsolatok megjelenítésére. A szöveg a piramis háttér fölötti téglalap alakzatokban jelenik meg. |
| RadialCluster | `92` | Használja olyan adat megjelenítésére, amely központi ötlethez vagy témához kapcsolódik. A legfelső Level 1 szöveg a középpontban jelenik meg. A Level 2 szöveg a körülötte lévő alakzatokban. Legfeljebb hét Level 2 alakzatot tartalmazhat. A fel nem használt szöveg nem jelenik meg, de elérhető marad, ha átvált a elrendezéseket. Legjobb kis mennyiségű szövegnél. |
| RadialCycle | `93` | Használja a központi ötlethez való kapcsolat megjelenítésére. Hangsúlyozza a központi körben lévő információt és azt, hogy a külső körök hogyan járulnak hozzá a központi ötlethez. Az első Level 1 sor a központi körnek felel meg, a hozzá tartozó Level 2 szöveg a külső körgyűrűnek. A fel nem használt szöveg nem jelenik meg, de elérhető marad, ha átvált a elrendezéseket. |
| RadialList | `94` | Használja a központi ötlethez való kapcsolatok ciklikus megjelenítésére. A központi alakzat képet tartalmazhat. A Level 1 szöveg a kisebb körökben jelenik meg, a kapcsolódó Level 2 szöveg a körök oldalán. |
| RadialVenn | `95` | Használja az átfedő kapcsolatok és a központi ötlethez való kapcsolat ciklikus megjelenítésére. Az első Level 1 sor a központi alakzatnak, a Level 2 sorok a körülötte lévő kör alakzatoknak felelnek meg. A fel nem használt szöveg nem jelenik meg, de elérhető marad, ha átvált a elrendezéseket. |
| RandomToResultProcess | `96` | Használja egy lépéssorozaton keresztül megmutatni, hogyan eredményezhetnek több kaotikus ötlet egy egységes cél vagy ötlet. Több Level 1 szöveget támogat, de az első és az utolsó Level 1 alakzat rögzített. Legjobban kis mennyiségű Level 1 szövegnél és közepes mennyiségű Level 2 szövegnél működik. |
| RepeatingBendingProcess | `97` | Használja egy feladat, folyamat vagy munkafolyamat során a fejlődés vagy sorozatos lépések megjelenítésére. Maximálja a alakzatok vízszintes és függőleges megjelenítési területét. |
| ReverseList | `98` | Használja két elem közötti váltás megjelenítésére. Csak az első két szövegelem jelenik meg, és minden elem nagy mennyiségű szöveget tartalmazhat. Jól használható két elem közti változás vagy sorrendváltás ábrázolására. |
| SegmentedCycle | `99` | Használja a fejlődés vagy egy szakasz, feladat vagy esemény sorozatának körkörös áramlásban történő megjelenítésére. Hangsúlyozza az összekapcsolt elemeket. A Level 1 szöveg első hét sora egy szelet vagy torta alakzatnak felel meg. A fel nem használt szöveg nem jelenik meg, de elérhető marad, ha átvált a elrendezéseket. |
| SegmentedProcess | `100` | Használja egy feladat, folyamat vagy munkafolyamat során a fejlődés vagy sorozatos lépések megjelenítésére. Hangsúlyozza a Level 2 szöveget, mivel minden sor külön alakzatban jelenik meg. |
| SegmentedPyramid | `101` | Használja tartalmazási, arányos vagy összekapcsolt kapcsolatok megjelenítésére. A Level 1 szöveg első kilenc sora a háromszög alakzatokban jelenik meg. A fel nem használt szöveg nem jelenik meg, de elérhető marad, ha átvált a elrendezéseket. Legjobban csak Level 1 szöveggel működik. |
| SnapshotPictureList | `102` | Használja képek magyarázó szöveggel való megjelenítésére. A Level 2 szöveg információlistákat jeleníthet meg. Nagy mennyiségű szövegnél működik jól. |
| SpiralPicture | `103` | Használja legfeljebb öt kép sorozatának megjelenítésére, a megfelelő Level 1 felirattal, amely spirálisan a középpont felé halad. |
| SquareAccentList | `104` | Használja információlisták kategóriákra bontott megjelenítésére. A Level 2 szöveg egy kis négyzet alakzat mellett jelenik meg. Nagy mennyiségű Level 2 szövegnél működik jól. |
| StackedList | `105` | Használja információcsoportok vagy lépések feladat, folyamat vagy munkafolyamat során történő megjelenítésére. A kör alakzatok Level 1 szöveget tartalmaznak, a megfelelő téglalapok Level 2 szöveget. Számos részlet és minimális Level 1 szöveg esetén működik jól. |
| StackedVenn | `106` | Használja átfedő kapcsolatok megjelenítésére. Jó választás a növekedés vagy fokozat kiemeléséhez. Leginkább csak Level 1 szöveggel működik a legjobban. Az első hét Level 1 sor egy kör alakú alakzathoz tartozik. A nem használt szöveg nem jelenik meg, de elérhető marad, ha elrendezettséget vált. |
| StaggeredProcess | `107` | Használja egy lefelé haladó szakaszok szerinti folyamat megjelenítésére. Az első öt Level 1 sor egy téglalappal egyezik. A nem használt szöveg nem jelenik meg, de elérhető marad, ha elrendezést vált. |
| StepDownProcess | `108` | Használja egy lefelé haladó folyamat több lépéssel és al-lépésekkel való megjelenítésére. Leginkább kis mennyiségű szöveggel működik a legjobban. |
| StepUpProcess | `109` | Használja egy felfelé haladó lépéssorozat vagy információlisták megjelenítésére. |
| SubStepProcess | `110` | Használja többlépéses folyamat, al-lépésekkel minden Level 1 szöveg példány között való megjelenítésére. Leginkább kis mennyiségű szöveggel működik, és legfeljebb hét Level 1 lépésre korlátozódik. Minden Level 1 lépésnek korlátlan számú al-lépése lehet. |
| TableHierarchy | `111` | Használja információcsoportok, felülről lefelé építve, valamint az egyes csoportok hierarchiáinak megjelenítésére. Ez az elrendezés nem tartalmaz összekötő vonalakat. |
| TableList | `112` | Használja egyenlő értékű csoportosított vagy kapcsolódó információk megjelenítésére. Az első Level 1 szövegsor a felső alakzathoz tartozik, és annak Level 2 szövegét használják a további listákhoz. |
| TargetList | `113` | Használja egymással összefüggő vagy átfedő információk megjelenítésére. Az első hét Level 1 szövegsor a téglalap alakzatban jelenik meg. A nem használt szöveg nem jelenik meg, de elérhető marad, ha elrendezést vált. Jól működik mind Level 1, mind Level 2 szöveggel. |
| TextCycle | `114` | Használja a szakaszok, feladatok vagy események folyamatos sorozatának körkörös áramlásban való ábrázolására. A nyilakat vagy az áramlást emeli ki a szakaszok vagy lépések helyett. Leginkább csak Level 1 szöveggel működik a legjobban. |
| TitlePictureLineup | `115` | Használja egy sor kép megjelenítésére, ahol mindegyiknek saját címe és leírása van. A Level 1 szöveg a kép feletti dobozban jelenik meg. A Level 2 szöveg a kép alatt jelenik meg. |
| TitledMatrix | `116` | Használja a négy kvadráns és az egész közötti kapcsolatok megjelenítésére. Az első Level 1 szövegsor a központi alakzathoz tartozik, és az első négy Level 2 szövegsor a kvadránsokban jelenik meg. A nem használt szöveg nem jelenik meg, de elérhető marad, ha elrendezést vált. |
| TitledPictureAccentList | `117` | Használja információlisták megjelenítésére, ahol minden Level 2 szöveghez egy kiemelő kép tartozik. A Level 1 szöveg külön dobozban jelenik meg a lista tetején. |
| TitledPictureBlocks | `118` | Használja egy sor kép megjelenítésére. A Level 1 szöveg minden kép felett jelenik meg. A Level 2 szöveg a képen oldalra, kissé átfedve jelenik meg. |
| TrapezoidList | `119` | Használja egyenlő értékű csoportosított vagy kapcsolódó információk megjelenítésére. Nagy mennyiségű szöveggel jól működik. |
| UpwardArrow | `120` | Használja egy felfelé irányuló feladat, folyamat vagy munkafolyamat lépéseinek vagy előrehaladásának megjelenítésére. Az első öt Level 1 szövegsor egy nyílponthoz tartozik. Leginkább minimális szöveggel működik a legjobban. A nem használt szöveg nem jelenik meg, de elérhető marad, ha elrendezést vált. |
| VerticalAccentList | `121` | Használja információlisták megjelenítésére. A Level 2 szöveg téglalap alakú formákban jelenik meg függőleges siroseken. A Level 2 szöveget emeli ki a Level 1 szöveghez képest, és közepes mennyiségű Level 2 szöveghez jó választás. |
| VerticalArrowList | `122` | Használja egy feladat, folyamat vagy munkafolyamat előrehaladásának vagy egymásutáni lépéseinek megjelenítésére, amelyek egy közös cél felé haladnak. Jó választás felsorolásos információlistákhoz. |
| VerticalBendingProcess | `123` | Használja egy feladat, folyamat vagy munkafolyamat előrehaladásának vagy egymásutáni lépéseinek megjelenítésére. Maximalizálja a formák vízszintes és függőleges megjelenítési helyét. Inkább a formák közötti kapcsolatokra helyezi a hangsúlyt, mint az irányra vagy a mozgásra. |
| VerticalBlockList | `124` | Használja információcsoportok vagy lépések megjelenítésére egy feladat, folyamat vagy munkafolyamat során. Nagy mennyiségű Level 2 szöveggel jól működik. Jó választás olyan szövegekhez, amelyeknek egy fő pontjuk és több al-pontja van. |
| VerticalBoxList | `125` | Használja több információcsoport megjelenítésére, különösen nagy mennyiségű Level 2 szöveget tartalmazó csoportok esetén. Jó választás felsorolásos információlistákhoz. |
| VerticalBulletList | `126` | Használja nem sorozatos vagy csoportosított információs blokkok megjelenítésére. Jó választás hosszú címsorokkal vagy felső szintű információval rendelkező listákhoz. |
| VerticalChevronList | `127` | Használja egy feladat, folyamat vagy munkafolyamat előrehaladásának vagy egymásutáni lépéseinek megjelenítésére, vagy a mozgás vagy irány kiemelésére. A Level 2 szöveget emeli ki a Level 1 szöveghez képest, és nagy mennyiségű Level 2 szöveghez jó választás. |
| VerticalCircleList | `128` | Használja sorozatos vagy csoportosított adatok megjelenítésére. Leginkább Level 1 szöveggel működik a legjobban, amely egy nagy kör alakú alakzat mellett jelenik meg. Az alacsonyabb szintű szövegek kisebb kör alakú alakzatokkal vannak elválasztva. |
| VerticalCurvedList | `129` | Használja ívelt információlisták megjelenítésére. A kiemelő kör alakzatokhoz képek hozzáadásához alkalmazzon képkitöltést. |
| VerticalEquation | `130` | Használja sorozatos lépések vagy feladatok megjelenítésére, amelyek egy tervet vagy eredményt ábrázolnak. Az utolsó Level 1 szövegsor a nyíl után jelenik meg. Leginkább csak Level 1 szöveggel működik a legjobban. |
| VerticalPictureAccentList | `131` | Használja nem sorozatos vagy csoportosított információs blokkok megjelenítésére. A kis körök képek tárolására vannak tervezve. |
| VerticalPictureList | `132` | Használja nem sorozatos vagy csoportosított információs blokkok megjelenítésére. A bal oldalon lévő kis alakzatok képek tárolására vannak tervezve. |
| VerticalProcess | `133` | Használja egy feladat, folyamat vagy munkafolyamat előrehaladásának vagy egymásutáni lépéseinek felülről lefelé történő megjelenítésére. Leginkább Level 1 szöveggel működik a legjobban, mivel a függőleges hely korlátozott. |
| Custom | `134` | Egy egyedi elrendezési sablonnal rendelkező SmartArt diagramot ábrázol |
| PictureOrganizationChart | `135` | Használja hierarchikus információk vagy jelentési kapcsolatok megjelenítésére egy szervezetben, a megfelelő képekkel. Az asszisztens alakzat és a szervezeti diagram függőleges elrendezései elérhetők ezzel az elrendezéssel. |

### Lásd még

* névtér [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->