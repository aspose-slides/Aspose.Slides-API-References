---
title: SmartArtLayoutType
second_title: Aspose.Slides pro .NET - referenční příručka API
description: Reprezentuje typ rozvržení diagramu SmartArt.
type: docs
weight: 10640
url: /cs/aspose.slides.smartart/smartartlayouttype/
---
## SmartArtLayoutType výčet

Represents layout type of a SmartArt diagram.

```csharp
public enum SmartArtLayoutType
```

### Hodnoty

| Název | Hodnota | Popis |
| --- | --- | --- |
| AccentProcess | `0` | Použít k zobrazení postupu, časové osy nebo sekvenčních kroků v úkolu, procesu nebo pracovním postupu. Dobře funguje při ilustraci jak Level 1, tak Level 2 textu. |
| AccentedPicture | `1` | Použít k zobrazení ústředního fotografického nápadu s souvisejícími nápady po stranách. Horní Level 1 text se zobrazí nad ústředním obrázkem. Odpovídající text pro ostatní Level 1 tvary se zobrazí vedle malých kulatých obrázků. Toto rozvržení také dobře funguje bez textu. |
| AlternatingFlow | `2` | Použít k zobrazení skupin informací nebo sekvenčních kroků v úkolu, procesu nebo pracovním postupu. Zdůrazňuje interakci nebo vztahy mezi skupinami informací. |
| AlternatingHexagons | `3` | Použít k reprezentaci série propojených nápadů. Level 1 text se zobrazuje uvnitř hexagonů. Level 2 text se zobrazuje mimo tvary. |
| AlternatingPictureBlocks | `4` | Použít k zobrazení série obrázků shora dolů. Text se střídavě zobrazuje vpravo nebo vlevo od obrázku. |
| AlternatingPictureCircles | `5` | Použít k zobrazení sady obrázků s textem. Odpovídající text se zobrazuje ve středových kruzích s obrázky střídavě zleva doprava. |
| ArrowRibbon | `6` | Použít k zobrazení souvisejících nebo kontrastních konceptů s nějakým spojením, např. protichůdných sil. První dva řádky Level 1 textu jsou použity pro text v šipkách. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozvržení. |
| AscendingPictureAccentProcess | `7` | Použít k zobrazení vzestupné série obrázků s popisným textem. Nejlépe funguje s malým množstvím textu. |
| Balance | `8` | Použít k porovnání nebo zobrazení vztahu mezi dvěma nápady. Každý z prvních dvou řádků Level 1 textu odpovídá textu v horní části jedné strany středového bodu. Zdůrazňuje Level 2 text, který je omezen na čtyři tvary na každé straně středového bodu. Vyvážení se nakloní k té straně, která má nejvíce tvarů obsahujících Level 2 text. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozvržení. |
| BasicBendingProcess | `9` | Použít k zobrazení postupu nebo sekvenčních kroků v úkolu, procesu nebo pracovním postupu. Maximálně využívá vodorovný i svislý prostor pro tvary. |
| BasicBlockList | `10` | Použít k zobrazení nesekvenčních nebo seskupených bloků informací. Maximálně využívá vodorovný i svislý prostor pro tvary. |
| BasicChevronProcess | `11` | Použít k zobrazení postupu; časové osy; sekvenčních kroků v úkolu, procesu nebo pracovním postupu; nebo k zdůraznění pohybu či směru. Level 1 text se zobrazí uvnitř šipkového tvaru, zatímco Level 2 text se zobrazí pod šipkovými tvary. |
| BasicCycle | `12` | Použít k reprezentaci pokračující sekvence fází, úkolů nebo událostí v kruhovém průběhu. Zdůrazňuje fáze nebo kroky spíše než propojující šipky či tok. Nejlépe funguje pouze s Level 1 textem. |
| BasicMatrix | `13` | Použít k zobrazení vztahu komponent k celku ve kvadrantech. První čtyři řádky Level 1 textu se zobrazují v kvadrantech. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozvržení. |
| BasicPie | `14` | Použít k zobrazení, jak jednotlivé části tvoří celek. Prvních sedm řádků Level 1 textu odpovídá rovnoměrně rozloženým klínům nebo koláčovým tvarům. Horní tvar Level 1 textu se zobrazí mimo zbytek koláče pro zdůraznění. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozvržení. |
| BasicProcess | `15` | Použít k zobrazení postupu nebo sekvenčních kroků v úkolu, procesu nebo pracovním postupu. |
| BasicPyramid | `16` | Použít k zobrazení proporčních, propojených nebo hierarchických vztahů s největší komponentou dole a zužující se směrem nahoru. Level 1 text se zobrazuje v segmentech pyramidy a Level 2 text se zobrazuje ve tvarech vedle každého segmentu. |
| BasicRadial | `17` | Použít k zobrazení vztahu k ústřednímu nápadu v cyklu. První řádek Level 1 textu odpovídá centrálnímu tvaru a jeho Level 2 text odpovídá okolním kruhovým tvarům. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozvržení. |
| BasicTarget | `18` | Použít k zobrazení obsahu, stupňování nebo hierarchických vztahů. Prvních pět řádků Level 1 textu je spojeno s kruhem. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozvržení. |
| BasicTimeline | `19` | Použít k zobrazení sekvenčních kroků v úkolu, procesu nebo pracovním postupu, nebo k zobrazení informací o časové ose. Dobře funguje s jak Level 1, tak Level 2 textem. |
| BasicVenn | `20` | Použít k zobrazení překrývajících se nebo propojených vztahů. Prvních sedm řádků Level 1 textu odpovídá kruhu. Pokud je čtyři nebo méně řádků Level 1 textu, text je uvnitř kruhů. Pokud je více než čtyři řádky Level 1 textu, text je mimo kruhy. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozvržení. |
| BendingPictureAccentList | `21` | Použít k zobrazení nesekvenčních nebo seskupených bloků informací. Malé kruhové tvary jsou určeny k obsahu obrázků. Dobře funguje při ilustraci jak Level 1, tak Level 2 textu. Maximálně využívá vodorovný i svislý prostor pro tvary. |
| BendingPictureBlocks | `22` | Použít k zobrazení série obrázků. Rámeček pokrývající dolní roh může obsahovat malé množství textu. |
| BendingPictureCaption | `23` | Použít k zobrazení sekvenční série obrázků. Rámeček pokrývající dolní roh může obsahovat malé množství textu. |
| BendingPictureCaptionList | `24` | Použít k zobrazení série obrázků. Název a popis se zobrazí ve tvaru komentáře pod každým obrázkem. |
| BendingPictureSemiTransparentText | `25` | Použít k zobrazení série obrázků. Poloprůhledný rámeček pokrývá spodní část obrázku a obsahuje všechny úrovně textu. |
| BlockCycle | `26` | Použít k reprezentaci pokračující sekvence fází, úkolů nebo událostí v kruhovém toku. Zdůrazňuje fáze nebo kroky spíše než propojující šipky nebo tok. |
| BubblePictureList | `27` | Použít k zobrazení série obrázků. Může obsahovat až osm Level 1 obrázků. Nepoužitý text a obrázky se nezobrazují, ale zůstávají k dispozici při změně rozvržení. Nejlépe funguje s malým množstvím textu. |
| CaptionedPictures | `28` | Použít k zobrazení obrázků s více úrovněmi textu. Nejlépe funguje s malým množstvím Level 1 textu a středním množstvím Level 2 textu. |
| ChevronList | `29` | Použít k zobrazení postupu skrze několik procesů, které tvoří celkový pracovní tok. Také funguje při ilustraci kontrastních procesů. Level 1 text odpovídá prvnímu šipkovému tvaru vlevo, zatímco Level 2 text odpovídá horizontálním podkrokům pro každý tvar, který obsahuje Level 1 text. |
| CircleAccentTimeline | `30` | Použít k zobrazení série událostí nebo informací o časové ose. Level 1 text se zobrazuje vedle větších kruhových tvarů. Level 2 text se zobrazuje vedle menších kruhových tvarů. |
| CircleArrowProcess | `31` | Použít k zobrazení sekvenčních položek s doprovodným textem pro každou položku. Tento diagram nejlépe funguje s malým množstvím Level 1 textu. |
| CirclePictureHierarchy | `32` | Použít k zobrazení hierarchických informací nebo vztahů podřízenosti v organizaci. Obrázky se zobrazují v kruzích a odpovídající text se zobrazuje vedle obrázků. |
| CircleRelationship | `33` | Použít k zobrazení vztahu k ústřednímu nápadu nebo od něj. Level 2 text je přidáván nesekvenčně a je omezen na pět položek. Může existovat pouze jedna položka Level 1. |
| CircularBendingProcess | `34` | Použít k zobrazení dlouhé nebo nelineární sekvence kroků v úkolu, procesu nebo pracovním postupu. Nejlépe funguje pouze s Level 1 textem. Maximálně využívá vodorovný i svislý prostor pro tvary. |
| CircularPictureCallout | `35` | Použít k zobrazení ústředního nápadu a podnápadů nebo souvisejících položek. Text pro první obrázek pokrývá spodní část obrázku. Odpovídající text pro ostatní Level 1 tvary se zobrazuje vedle malých kulatých obrázků. Tento diagram také dobře funguje bez textu. |
| ClosedChevronProcess | `36` | Použít k zobrazení postupu, časové osy nebo sekvenčních kroků v úkolu, procesu nebo pracovním postupu, nebo k zdůraznění pohybu či směru. Lze použít k zdůraznění informací v počátečním tvaru. Nejlépe funguje pouze s Level 1 textem. |
| ContinuousArrowProcess | `37` | Použít k zobrazení časové osy nebo sekvenčních kroků v úkolu, procesu nebo pracovním postupu. Nejlépe funguje s Level 1 textem, protože každý řádek Level 1 textu se zobrazí uvnitř šipkového tvaru. Level 2 text se zobrazí mimo šipkový tvar. |
| ContinuousBlockProcess | `38` | Použít k zobrazení postupu nebo sekvenčních kroků v úkolu, procesu nebo pracovním postupu. Nejlépe funguje s minimálním množstvím Level 1 a Level 2 textu. |
| ContinuousCycle | `39` | Použít k reprezentaci pokračující sekvence fází, úkolů nebo událostí v kruhovém toku. Zdůrazňuje spojení mezi všemi komponentami. Nejlépe funguje pouze s Level 1 textem. |
| ContinuousPictureList | `40` | Použít k zobrazení skupin propojených informací. Kružové tvary jsou navrženy tak, aby obsahovaly obrázky. |
| ConvergingArrows | `41` | Použít k zobrazení nápadů nebo konceptů, které se sbíhají do ústředního bodu. Nejlépe funguje pouze s Level 1 textem. |
| ConvergingRadial | `42` | Použít k zobrazení vztahů konceptů nebo komponent k ústřednímu nápadu v cyklu. První řádek Level 1 textu odpovídá centrálnímu kruhovému tvaru a řádky Level 2 textu odpovídají okolním obdélníkovým tvarům. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozvržení. |
| CounterbalanceArrows | `43` | Použít k zobrazení dvou protichůdných nápadů nebo konceptů. Každý z prvních dvou řádků Level 1 textu odpovídá šipce a dobře funguje s Level 2 textem. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozvržení. |
| CycleMatrix | `44` | Použít k zobrazení vztahu k ústřednímu nápadu v cyklickém postupu. Každý z prvních čtyř řádků Level 1 textu odpovídá klínu nebo koláčovému tvaru a Level 2 text se zobrazuje v obdélníkovém tvaru po straně klínu nebo koláčového tvaru. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozvržení. |
| DescendingBlockList | `45` | Použít k zobrazení skupin souvisejících nápadů nebo seznamů informací. Textové tvary postupně klesají výškově a Level 1 text se zobrazuje vertikálně. |
| DescendingProcess | `46` | Použít k zobrazení sestupné série událostí. První Level 1 text je na vrcholu šipky a poslední Level 1 text se zobrazuje na spodní části šipky. Zobrazí se jen prvních sedm položek Level 1. Nejlépe funguje s malým až středním množstvím textu. |
| DetailedProcess | `47` | Použít s velkým množstvím Level 2 textu k zobrazení postupu skrze fáze. |
| DivergingArrows | `48` | Použít k zobrazení nápadů nebo konceptů, které se rozšiřují od ústředního zdroje. Nejlépe funguje pouze s Level 1 textem. |
| DivergingRadial | `49` | Použít k zobrazení vztahů k ústřednímu nápadu v cyklu. První řádek Level 1 textu odpovídá centrálnímu kruhovému tvaru. Zdůrazňuje okolní kruhy spíše než ústřední nápad. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozvržení. |
| Equation | `50` | Použít k zobrazení sekvenčních kroků nebo úkolů, které představují plán nebo výsledek. Poslední řádek Level 1 textu se objeví po rovnítku (=). Nejlépe funguje pouze s Level 1 textem. |
| FramedTextPicture | `51` | Použít k zobrazení obrázků s odpovídajícím Level 1 textem zobrazeným v rámečku. |
| Funnel | `52` | Použít k zobrazení filtrování informací nebo toho, jak se části spojují do celku. Zdůrazňuje konečný výsledek. Může obsahovat až čtyři řádky Level 1 textu; poslední z těchto čtyř řádků Level 1 textu se zobrazí pod trychtýřem a ostatní řádky odpovídají kruhovému tvaru. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozvržení. |
| Gear | `53` | Použijte k zobrazení propojených myšlenek. Každá ze tří prvních řádků textu úrovně 1 odpovídá tvaru ozubeného kola a jejich odpovídající text úrovně 2 se zobrazí v obdélnících vedle tvaru ozubeného kola. Nepoužitý text se nezobrazí, ale zůstane k dispozici, pokud přepnete rozvržení. |
| GridMatrix | `54` | Použijte k zobrazení rozmístění konceptů podél dvou os. Zdůrazňuje jednotlivé komponenty spíše než celek. První čtyři řádky textu úrovně 1 se objeví v kvadrantech. Nepoužitý text se nezobrazí, ale zůstane k dispozici, pokud přepnete rozvržení. |
| GroupedList | `55` | Použijte k zobrazení skupin a podskupin informací nebo kroků a podkroků v úkolu, procesu či pracovním postupu. Text úrovně 1 odpovídá horizontálním tvarům nejvyšší úrovně a text úrovně 2 odpovídá vertikálním podkrokům pod každým souvisejícím tvarem nejvyšší úrovně. Hodí se k zdůraznění podskupin nebo podkroků, hierarchických informací nebo více seznamů informací. |
| HalfCircleOrganizationChart | `56` | Použijte k zobrazení hierarchických informací nebo vztahů podřízenosti v organizaci. Asistentské tvary a visící rozvržení organogramu jsou s tímto rozvržením k dispozici. |
| HexagonCluster | `57` | Použijte k zobrazení obrázků s přidruženým popisným textem. Malé šestiúhelníky označují dvojici obrázek-text. Funguje nejlépe při malém množství textu. |
| Hierarchy | `58` | Použijte k zobrazení hierarchických vztahů postupujících shora dolů. |
| HierarchyList | `59` | Použijte k zobrazení hierarchických vztahů postupujících napříč skupinami. Lze také použít k seskupení nebo výčtu informací. |
| HorizontalBulletList | `60` | Použijte k zobrazení nesekvenčních nebo seskupených seznamů informací. Dobře funguje při velkém množství textu. Veškerý text má stejnou úroveň důrazu a směr není naznačen. |
| HorizontalHierarchy | `61` | Použijte k zobrazení hierarchických vztahů postupujících horizontálně. Hodí se pro rozhodovací stromy. |
| HorizontalLabeledHierarchy | `62` | Použijte k zobrazení hierarchických vztahů postupujících horizontálně a seskupených hierarchicky. Zdůrazňuje nadpis nebo text úrovně 1. První řádek textu úrovně 1 se zobrazuje ve tvaru na začátku hierarchie a druhý a všechny následující řádky textu úrovně 1 se zobrazují v horní části vysokých obdélníků. |
| HorizontalMultiLevelHierarchy | `63` | Použijte k zobrazení velkého množství hierarchických informací postupujících horizontálně. Vrchol hierarchie je zobrazen vertikálně. Toto rozvržení podporuje mnoho úrovní v hierarchii. |
| HorizontalOrganizationChart | `64` | Použijte k zobrazení hierarchických informací horizontálně nebo vztahů podřízenosti v organizaci. Asistentský tvar a visící rozvržení organogramu jsou s tímto rozvržením k dispozici. |
| HorizontalPictureList | `65` | Použijte k zobrazení nesekvenčních nebo seskupených informací s důrazem na související obrázky. Horní tvary jsou navrženy tak, aby obsahovaly obrázky. |
| IncreasingArrowsProcess | `66` | Použijte k zobrazení sekvenčních a překrývajících se kroků v procesu. Omezeno na pět položek úrovně 1. Úroveň 2 může obsahovat velké množství textu. |
| IncreasingCircleProcess | `67` | Použijte k zobrazení série kroků, přičemž vnitřek kruhu se s každým krokem zvětšuje. Omezeno na sedm kroků úrovně 1, ale neomezený počet položek úrovně 2. Funguje dobře s velkým množstvím textu úrovně 2. |
| InvertedPyramid | `68` | Použijte k zobrazení proporčních, provázaných nebo hierarchických vztahů s největší součástí nahoře a zužováním dolů. Text úrovně 1 se objevuje v segmentech pyramidy a text úrovně 2 v tvarech podél každého segmentu. |
| LabeledHierarchy | `69` | Použijte k zobrazení hierarchických vztahů postupujících shora dolů a hierarchicky seskupených. Zdůrazňuje nadpis nebo text úrovně 1. První řádek textu úrovně 1 se zobrazuje ve tvaru na začátku hierarchie a všechny následující řádky textu úrovně 1 se zobrazují vlevo od dlouhých obdélníků. |
| LinearVenn | `70` | Použijte k zobrazení překrývajících se vztahů v sekvenci. Funguje nejlépe jen s textem úrovně 1. |
| LinedList | `71` | Použijte k zobrazení velkého množství textu rozděleného do kategorií a podkategorií. Dobře funguje s více úrovněmi textu. Text na stejné úrovni je oddělen řádky. |
| MultidirectionalCycle | `72` | Použijte k zobrazení kontinuální sekvence fází, úkolů nebo událostí, které mohou nastat v libovolném směru. |
| NameandTitleOrganizationChart | `73` | Použijte k zobrazení hierarchických informací nebo vztahů podřízenosti v organizaci. Pro zadání textu do políčka nadpisu píšte přímo do menšího obdélníkového tvaru. Asistentský tvar a visící rozvržení organogramu jsou s tímto rozvržením k dispozici. |
| NestedTarget | `74` | Použijte k zobrazení vztahů obsahování. Každý ze tří prvních řádků textu úrovně 1 odpovídá levému hornímu textu ve tvarech a text úrovně 2 odpovídá menším tvarům. Nejlépe funguje s minimálním počtem řádků textu úrovně 2. Nepoužitý text se nezobrazí, ale zůstane k dispozici, pokud přepnete rozvržení. |
| NondirectionalCycle | `75` | Použijte k zobrazení kontinuální sekvence fází, úkolů nebo událostí v kruhovém toku. Každý tvar má stejnou úroveň významu. Dobře funguje, když není potřeba naznačovat směr. |
| OpposingArrows | `76` | Použijte k zobrazení dvou protichůdných myšlenek nebo myšlenek, které se odklánějí od centrálního bodu. Každý ze dvou prvních řádků textu úrovně 1 odpovídá šipce. Nepoužitý text se nezobrazí, ale zůstane k dispozici, pokud přepnete rozvržení. |
| OpposingIdeas | `77` | Použijte k zobrazení dvou protichůdných nebo kontrastních myšlenek. Může mít jednu nebo dvě položky úrovně 1. Každý text úrovně 1 může obsahovat více podúrovní. Dobře funguje s velkým množstvím textu. |
| OrganizationChart | `78` | Použijte k zobrazení hierarchických informací nebo vztahů podřízenosti v organizaci. Asistentský tvar a visící rozvržení organogramu jsou s tímto rozvržením k dispozici. |
| PhasedProcess | `79` | Použijte k zobrazení tří fází procesu. Omezeno na tři položky úrovně 1. První dvě položky úrovně 1 mohou každá obsahovat čtyři položky úrovně 2 a třetí položka úrovně 1 může obsahovat neomezený počet položek úrovně 2. Nejlépe funguje s malým množstvím textu. |
| PictureAccentBlocks | `80` | Použijte k zobrazení skupiny obrázků v blocích vycházejících z rohu. Odpovídající text se zobrazuje vertikálně. Dobře funguje jako akcent na snímcích s titulkem nebo podtitulkem nebo pro oddíly v dokumentu. |
| PictureAccentList | `81` | Použijte k zobrazení seskupených nebo souvisejících informací. Malé tvary v horních rozích jsou navrženy tak, aby obsahovaly obrázky. Zdůrazňuje text úrovně 2 nad textem úrovně 1 a je vhodnou volbou pro velké množství textu úrovně 2. |
| PictureAccentProcess | `82` | Použijte k zobrazení sekvenčních kroků v úkolu, procesu nebo pracovním postupu. Obdélníkové tvary v pozadí jsou navrženy tak, aby obsahovaly obrázky. |
| PictureCaptionList | `83` | Použijte k zobrazení nesekvenčních nebo seskupených bloků informací. Horní tvary jsou navrženy tak, aby obsahovaly obrázky a obrázky jsou zvýrazněny nad textem. Dobře funguje pro obrázky s krátkými textovými popisky. |
| PictureGrid | `84` | Použijte k zobrazení obrázků uspořádaných na čtvercovém mřížkovém uspořádání. Nejlepší s malým množstvím textu úrovně 1, který se zobrazuje nad obrázkem. |
| PictureLineup | `85` | Použijte k zobrazení série obrázků vedle sebe. Text úrovně 1 pokrývá horní část obrázku. Text úrovně 2 se objeví pod obrázkem. |
| PictureStrips | `86` | Použijte k zobrazení série obrázků shora dolů s textem úrovně 1 vedle každého. |
| PieProcess | `87` | Použijte k zobrazení kroků v procesu, přičemž každý výseč koláče se zvětšuje až na sedm tvarů. Text úrovně 1 se zobrazuje vertikálně. |
| PlusandMinus | `88` | Použijte k zobrazení výhod a nevýhod dvou myšlenek. Každý text úrovně 1 může obsahovat více podúrovní. Dobře funguje s velkým množstvím textu. Omezeno na dvě položky úrovně 1. |
| ProcessArrows | `89` | Použijte k zobrazení informací ilustrujících proces nebo pracovní postup. Text úrovně 1 se objevuje v kruhových tvarech a text úrovně 2 ve tvaru šipek. Nejlépe funguje při minimálním množství textu a pro zdůraznění pohybu nebo směru. |
| ProcessList | `90` | Použijte k zobrazení více skupin informací nebo kroků a podkroků v úkolu, procesu či pracovním postupu. Text úrovně 1 odpovídá horním horizontálním tvarům a text úrovně 2 odpovídá vertikálním podkrokům pod každým souvisejícím tvarem nejvyšší úrovně. |
| PyramidList | `91` | Použijte k zobrazení proporčních, provázaných nebo hierarchických vztahů. Text se zobrazí v obdélníkových tvarech na pozadí pyramidy. |
| RadialCluster | `92` | Použijte k zobrazení dat souvisejících s centrální myšlenkou nebo tématem. Horní text úrovně 1 se objeví ve středu. Text úrovně 2 se objevuje v okolních tvarech. Může obsahovat až sedm tvarů úrovně 2. Nepoužitý text se nezobrazí, ale zůstane k dispozici, pokud přepnete rozvržení. Nejlépe funguje s malým množstvím textu. |
| RadialCycle | `93` | Použijte k zobrazení vztahu k centrální myšlence. Zdůrazňuje jak informace ve středovém kruhu, tak to, jak informace vnějšího prstence kruhů přispívají k centrální myšlence. První řádek textu úrovně 1 odpovídá středovému kruhu a jeho text úrovně 2 odpovídá vnějšímu prstenci kruhů. Nepoužitý text se nezobrazí, ale zůstane k dispozici, pokud přepnete rozvržení. |
| RadialList | `94` | Použijte k zobrazení vztahů k centrální myšlence v cyklu. Střední tvar může obsahovat obrázek. Text úrovně 1 se objevuje v menších kruzích a související text úrovně 2 se zobrazuje po straně menších kruhů. |
| RadialVenn | `95` | Použijte k zobrazení jak překrývajících se vztahů, tak vztahu k centrální myšlence v cyklu. První řádek textu úrovně 1 odpovídá centrálnímu tvaru a řádky textu úrovně 2 odpovídají okolním kruhovým tvarům. Nepoužitý text se nezobrazí, ale zůstane k dispozici, pokud přepnete rozvržení. |
| RandomToResultProcess | `96` | Použijte k zobrazení, jak prostřednictvím série kroků může několik chaotických myšlenek vést k jednotnému cíli nebo myšlence. Podporuje více položek textu úrovně 1, ale první a poslední tvar odpovídající úrovni 1 jsou pevně dané. Nejlépe funguje s malým množstvím textu úrovně 1 a středním množstvím textu úrovně 2. |
| RepeatingBendingProcess | `97` | Použijte k zobrazení postupu nebo sekvenčních kroků v úkolu, procesu či pracovním postupu. Maximalizuje jak horizontální, tak vertikální zobrazovací prostor pro tvary. |
| ReverseList | `98` | Použijte k přepínání mezi dvěma položkami. Zobrazí se jen první dva textové položky a každá položka může obsahovat velké množství textu. Dobře funguje k zobrazení změny mezi dvěma položkami nebo posunu v pořadí. |
| SegmentedCycle | `99` | Použijte k zobrazení postupu nebo sekvence fází, úkolů či událostí v kruhovém toku. Zdůrazňuje provázané části. Každý ze sedmi prvních řádků textu úrovně 1 odpovídá výseči nebo tvaru koláče. Nepoužitý text se nezobrazí, ale zůstane k dispozici, pokud přepnete rozvržení. |
| SegmentedProcess | `100` | Použijte k zobrazení postupu nebo sekvenčních kroků v úkolu, procesu či pracovním postupu. Zdůrazňuje text úrovně 2, protože každý řádek se objeví v samostatném tvaru. |
| SegmentedPyramid | `101` | Použijte k zobrazení vztahů obsahování, proporčních nebo provázaných vztahů. Prvních devět řádků textu úrovně 1 se objeví v trojúhelníkových tvarech. Nepoužitý text se nezobrazí, ale zůstane k dispozici, pokud přepnete rozvržení. Nejlépe funguje pouze s textem úrovně 1. |
| SnapshotPictureList | `102` | Použijte k zobrazení obrázků s vysvětlujícím textem. Text úrovně 2 může zobrazovat seznamy informací. Dobře funguje s velkým množstvím textu. |
| SpiralPicture | `103` | Použijte k zobrazení série až pěti obrázků s odpovídajícími titulky úrovně 1, které se spirálovitě stáčejí do středu. |
| SquareAccentList | `104` | Použijte k zobrazení seznamů informací rozdělených do kategorií. Text úrovně 2 se objevuje vedle malého čtvercového tvaru. Dobře funguje s velkým množstvím textu úrovně 2. |
| StackedList | `105` | Použijte k zobrazení skupin informací nebo kroků v úkolu, procesu či pracovním postupu. Kruhové tvary obsahují text úrovně 1 a odpovídající obdélníky obsahují text úrovně 2. Dobře funguje pro velké množství detailů a minimální text úrovně 1.
| StackedVenn | `106` | Používá se k zobrazení překrývajících se vztahů. Dobrá volba pro zdůraznění růstu nebo stupňování. Funguje nejlépe pouze s textem úrovně 1. Prvních sedm řádků textu úrovně 1 odpovídá kruhovému tvaru. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozvržení. |
| StaggeredProcess | `107` | Používá se k zobrazení sestupného postupu skrze fáze. Každý z prvních pěti řádků textu úrovně 1 odpovídá obdélníku. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozvržení. |
| StepDownProcess | `108` | Používá se k zobrazení sestupného procesu s více kroky a podkroky. Funguje nejlépe s malým množstvím textu. |
| StepUpProcess | `109` | Používá se k zobrazení vzestupné řady kroků nebo seznamů informací. |
| SubStepProcess | `110` | Používá se k zobrazení vícefázového procesu s podkroky mezi jednotlivými výskyty textu úrovně 1. Funguje nejlépe s malým množstvím textu a je omezeno na sedm kroků úrovně 1. Každý krok úrovně 1 může mít neomezený počet podkroků. |
| TableHierarchy | `111` | Používá se k zobrazení skupin informací vytvořených shora dolů a hierarchií v rámci každé skupiny. Toto rozvržení neobsahuje spojovací čáry. |
| TableList | `112` | Používá se k zobrazení seskupených nebo souvisejících informací stejné hodnoty. První řádek textu úrovně 1 odpovídá hornímu tvaru a jeho text úrovně 2 se používá pro následné seznamy. |
| TargetList | `113` | Používá se k zobrazení vzájemně souvisejících nebo překrývajících se informací. Každý z prvních sedmi řádků textu úrovně 1 se zobrazí v obdélníkovém tvaru. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozvržení. Dobře funguje jak s textem úrovně 1, tak úrovně 2. |
| TextCycle | `114` | Používá se k zobrazení pokračující posloupnosti fází, úkolů nebo událostí v kruhovém toku. Zdůrazňuje šipky nebo tok spíše než fáze či kroky. Funguje nejlépe pouze s textem úrovně 1. |
| TitlePictureLineup | `115` | Používá se k zobrazení série obrázků, z nichž každý má vlastní titulek a popis. Text úrovně 1 se zobrazuje v rámečku nad obrázkem. Text úrovně 2 se zobrazuje pod obrázkem. |
| TitledMatrix | `116` | Používá se k zobrazení vztahů čtyř kvadrantů k celku. První řádek textu úrovně 1 odpovídá centrálnímu tvaru a první čtyři řádky textu úrovně 2 se zobrazí v kvadrantech. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozvržení. |
| TitledPictureAccentList | `117` | Používá se k zobrazení seznamů informací s doplňujícím obrázkem pro každý text úrovně 2. Text úrovně 1 se zobrazuje v samostatném rámečku v horní části seznamu. |
| TitledPictureBlocks | `118` | Používá se k zobrazení série obrázků. Text úrovně 1 se zobrazuje nad každým obrázkem. Text úrovně 2 se zobrazuje po straně a mírně překrývá každý obrázek. |
| TrapezoidList | `119` | Používá se k zobrazení seskupených nebo souvisejících informací stejné hodnoty. Dobře funguje s velkým množstvím textu. |
| UpwardArrow | `120` | Používá se k zobrazení postupu nebo kroků, které v úkolu, procesu nebo pracovním postupu směřují vzhůru. Každý z prvních pěti řádků textu úrovně 1 odpovídá bodu na šipce. Funguje nejlépe s minimálním textem. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozvržení. |
| VerticalAccentList | `121` | Používá se k zobrazení seznamů informací. Text úrovně 2 se zobrazuje v obdélníkových tvarech nad vertikálními šipkami. Zdůrazňuje text úrovně 2 nad textem úrovně 1 a je vhodný pro střední množství textu úrovně 2. |
| VerticalArrowList | `122` | Používá se k zobrazení postupu nebo sekvenčních kroků v úkolu, procesu nebo pracovním postupu směřujících k společnému cíli. Dobře funguje pro odrážkové seznamy informací. |
| VerticalBendingProcess | `123` | Používá se k zobrazení postupu nebo sekvenčních kroků v úkolu, procesu nebo pracovním postupu. Maximalizuje jak vodorovný, tak svislý prostor pro tvary. Dává větší důraz na vzájemné vztahy mezi tvary než na směr či pohyb. |
| VerticalBlockList | `124` | Používá se k zobrazení skupin informací nebo kroků v úkolu, procesu či pracovním postupu. Dobře funguje s velkým množstvím textu úrovně 2. Je vhodný pro text s hlavním bodem a více podbody. |
| VerticalBoxList | `125` | Používá se k zobrazení několika skupin informací, zejména skupin s velkým množstvím textu úrovně 2. Je vhodný pro odrážkové seznamy informací. |
| VerticalBulletList | `126` | Používá se k zobrazení nesekvenčních nebo seskupených bloků informací. Dobře funguje pro seznamy s dlouhými nadpisy nebo informacemi nejvyšší úrovně. |
| VerticalChevronList | `127` | Používá se k zobrazení postupu nebo sekvenčních kroků v úkolu, procesu nebo pracovním postupu nebo k zdůraznění pohybu či směru. Zdůrazňuje text úrovně 2 nad textem úrovně 1 a je vhodný pro velké množství textu úrovně 2. |
| VerticalCircleList | `128` | Používá se k zobrazení sekvenčních nebo seskupených dat. Funguje nejlépe pro text úrovně 1, který se zobrazuje vedle velkého kulatého tvaru. Nižší úrovně textu jsou odděleny menšími kulatými tvary. |
| VerticalCurvedList | `129` | Používá se k zobrazení zakřiveného seznamu informací. Pro přidání obrázků do akcentových kulatých tvarů použijte výplň obrázkem. |
| VerticalEquation | `130` | Používá se k zobrazení sekvenčních kroků nebo úkolů, které představují plán nebo výsledek. Poslední řádek textu úrovně 1 se zobrazí za šipkou. Funguje nejlépe pouze s textem úrovně 1. |
| VerticalPictureAccentList | `131` | Používá se k zobrazení nesekvenčních nebo seskupených bloků informací. Malé kruhy jsou určené k umístění obrázků. |
| VerticalPictureList | `132` | Používá se k zobrazení nesekvenčních nebo seskupených bloků informací. Malé tvary vlevo jsou určeny k umístění obrázků. |
| VerticalProcess | `133` | Používá se k zobrazení postupu nebo sekvenčních kroků v úkolu, procesu nebo pracovním postupu shora dolů. Funguje nejlépe s textem úrovně 1, protože svislý prostor je omezený. |
| Custom | `134` | Představuje diagram SmartArt s vlastní šablonou rozvržení |
| PictureOrganizationChart | `135` | Používá se k zobrazení hierarchických informací nebo vztahů podřízenosti v organizaci s odpovídajícími obrázky. Asistentský tvar a rozvržení visící organizační schémata jsou s tímto rozvržením k dispozici. |

### Viz také

* jmenný prostor [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* sestava [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->