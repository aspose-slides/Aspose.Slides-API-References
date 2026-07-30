---
title: SmartArtLayoutType
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Reprezentuje typ rozložení diagramu SmartArt.
type: docs
weight: 157
url: /cs/aspose.slides.smartart/smartartlayouttype/
---
## SmartArtLayoutType enum

Reprezentuje typ rozvržení diagramu [SmartArt](../smartart/).

```cpp
enum class SmartArtLayoutType
```

### Hodnoty

| Název | Hodnota | Popis |
| --- | --- | --- |
| AccentProcess | 0 | Použít k zobrazení postupu, časové osy nebo sekvenčních kroků v úkolu, procesu nebo workflow. Dobře funguje při ilustraci jak textu úrovně 1, tak úrovně 2. |
| AccentedPicture | 1 | Použít k zobrazení centrální fotografické myšlenky s souvisejícími myšlenkami po straně. Horní text úrovně 1 se zobrazuje nad centrálním obrázkem. Odpovídající text pro další tvary úrovně 1 se zobrazuje vedle malých kruhových obrázků. Toto rozvržení také dobře funguje bez textu. |
| AlternatingFlow | 2 | Použít k zobrazení skupin informací nebo sekvenčních kroků v úkolu, procesu nebo workflow. Zdůrazňuje interakci nebo vztahy mezi skupinami informací. |
| AlternatingHexagons | 3 | Použít k reprezentaci série propojených nápadů. Text úrovně 1 se zobrazí uvnitř šestiúhelníků. Text úrovně 2 se zobrazí mimo tvary. |
| AlternatingPictureBlocks | 4 | Použít k zobrazení série obrázků shora dolů. Text se střídavě objevuje vpravo nebo vlevo od obrázku. |
| AlternatingPictureCircles | 5 | Použít k zobrazení sady obrázků s textem. Odpovídající text se zobrazí ve středových kruzích, přičemž obrázky se střídají zleva doprava. |
| ArrowRibbon | 6 | Použít k zobrazení souvisejících nebo kontrastních konceptů s nějakým propojením, například protichůdných sil. První dva řádky textu úrovně 1 jsou použity jako text v šipkách. Nepoužitý text se nezobrazí, ale zůstane k dispozici při změně rozvržení. |
| AscendingPictureAccentProcess | 7 | Použít k zobrazení vzestupné série obrázků s popisným textem. Nejlépe funguje s malým množstvím textu. |
| Balance | 8 | Použít k porovnání nebo zobrazení vztahu mezi dvěma nápady. Každý z prvních dvou řádků textu úrovně 1 odpovídá textu v horní části jedné strany středového bodu. Zdůrazňuje text úrovně 2, který je omezen na čtyři tvary na každé straně středového bodu. Váha se naklání ke straně s nejvíce tvary obsahujícími text úrovně 2. Nepoužitý text se nezobrazí, ale zůstane k dispozici při změně rozvržení. |
| BasicBendingProcess | 9 | Použít k zobrazení postupu nebo sekvenčních kroků v úkolu, procesu nebo workflow. Maximalizuje jak vodorovný, tak svislý prostor pro zobrazení tvarů. |
| BasicBlockList | 10 | Použít k zobrazení nesekvenčních nebo seskupených bloků informací. Maximalizuje jak vodorovný, tak svislý prostor pro zobrazení tvarů. |
| BasicChevronProcess | 11 | Použít k zobrazení postupu; časové osy; sekvenčních kroků v úkolu, procesu nebo workflow; nebo k zdůraznění pohybu či směru. Text úrovně 1 se zobrazuje uvnitř tvaru šipky, zatímco text úrovně 2 se zobrazí pod tvary šipek. |
| BasicCycle | 12 | Použít k reprezentaci pokračující sekvence fází, úkolů nebo událostí v kruhovém toku. Zdůrazňuje fáze nebo kroky spíše než propojující šipky nebo tok. Nejlépe funguje pouze s textem úrovně 1. |
| BasicMatrix | 13 | Použít k zobrazení vztahu komponent k celku v kvadrantech. První čtyři řádky textu úrovně 1 se zobrazí v kvadrantech. Nepoužitý text se nezobrazí, ale zůstane k dispozici při změně rozvržení. |
| BasicPie | 14 | Použít k zobrazení, jak jednotlivé části tvoří celek. Prvních sedm řádků textu úrovně 1 odpovídá rovnoměrně rozděleným segmentům nebo tvarům koláče. Horní tvar textu úrovně 1 se zobrazuje mimo zbytek koláče pro zdůraznění. Nepoužitý text se nezobrazí, ale zůstane k dispozici při změně rozvržení. |
| BasicProcess | 15 | Použít k zobrazení postupu nebo sekvenčních kroků v úkolu, procesu nebo workflow. |
| BasicPyramid | 16 | Použít k zobrazení poměrných, propojených nebo hierarchických vztahů s největší součástí dole a zužováním nahoru. Text úrovně 1 se zobrazí v segmentech pyramidy a text úrovně 2 se zobrazí ve tvarech vedle každého segmentu. |
| BasicRadial | 17 | Použít k zobrazení vztahu k centrální myšlence v cyklu. První řádek textu úrovně 1 odpovídá centrálnímu tvaru a jeho text úrovně 2 odpovídá okolním kruhovým tvarům. Nepoužitý text se nezobrazí, ale zůstane k dispozici při změně rozvržení. |
| BasicTarget | 18 | Použít k zobrazení zahrnutí, stupňování nebo hierarchických vztahů. Prvních pět řádků textu úrovně 1 je přiřazeno ke kruhu. Nepoužitý text se nezobrazí, ale zůstane k dispozici při změně rozvržení. |
| BasicTimeline | 19 | Použít k zobrazení sekvenčních kroků v úkolu, procesu nebo workflow nebo k zobrazení informací časové osy. Dobře funguje s textem úrovně 1 i úrovně 2. |
| BasicVenn | 20 | Použít k zobrazení překrývajících se nebo propojených vztahů. Prvních sedm řádků textu úrovně 1 odpovídá kruhu. Pokud je čtyři nebo méně řádků textu úrovně 1, je text uvnitř kruhů. Pokud je více než čtyři řádky textu úrovně 1, je text mimo kruhy. Nepoužitý text se nezobrazí, ale zůstane k dispozici při změně rozvržení. |
| BendingPictureAccentList | 21 | Použít k zobrazení nesekvenčních nebo seskupených bloků informací. Malé kruhové tvary jsou navrženy tak, aby obsahovaly obrázky. Dobře funguje při ilustraci textu úrovně 1 i úrovně 2. Maximalizuje jak vodorovný, tak svislý prostor pro zobrazení tvarů. |
| BendingPictureBlocks | 22 | Použít k zobrazení série obrázků. Box pokrývající dolní roh může obsahovat malé množství textu. |
| BendingPictureCaption | 23 | Použít k zobrazení sekvenční série obrázků. Box pokrývající dolní roh může obsahovat malé množství textu. |
| BendingPictureCaptionList | 24 | Použít k zobrazení série obrázků. Název a popis se zobrazí v bublinovém tvaru pod každým obrázkem. |
| BendingPictureSemiTransparentText | 25 | Použít k zobrazení série obrázků. Poloprůhledný box pokrývá spodní část obrázku a obsahuje všechny úrovně textu. |
| BlockCycle | 26 | Použít k reprezentaci pokračující sekvence fází, úkolů nebo událostí v kruhovém toku. Zdůrazňuje fáze nebo kroky spíše než propojující šipky nebo tok. |
| BubblePictureList | 27 | Použít k zobrazení série obrázků. Může obsahovat až osm obrázků úrovně 1. Nepoužitý text a obrázky se nezobrazí, ale zůstávají k dispozici při změně rozvržení. Nejlépe funguje s malým množstvím textu. |
| CaptionedPictures | 28 | Použít k zobrazení obrázků s více úrovněmi textu. Nejlépe funguje s malým množstvím textu úrovně 1 a středním množstvím textu úrovně 2. |
| ChevronList | 29 | Použít k zobrazení postupu skrze několik procesů, které tvoří celkový workflow. Také funguje při ilustraci kontrastních procesů. Text úrovně 1 odpovídá prvnímu tvaru šipky vlevo, zatímco text úrovně 2 odpovídá horizontálním podkrokům pro každý tvar, který obsahuje text úrovně 1. |
| CircleAccentTimeline | 30 | Použít k zobrazení série událostí nebo informací časové osy. Text úrovně 1 se zobrazuje vedle větších kruhových tvarů. Text úrovně 2 se zobrazuje vedle menších kruhových tvarů. |
| CircleArrowProcess | 31 | Použít k zobrazení sekvenčních položek s podporujícím textem pro každou položku. Tento diagram nejlépe funguje s malým množstvím textu úrovně 1. |
| CirclePictureHierarchy | 32 | Použít k zobrazení hierarchických informací nebo vztahů reportování v organizaci. Obrázky se objevují v kruzích a odpovídající text se zobrazuje vedle obrázků. |
| CircleRelationship | 33 | Použít k zobrazení vztahu k centrální myšlence nebo z ní. Text úrovně 2 se přidává nesekvenčně a je omezen na pět položek. Může existovat pouze jedna položka úrovně 1. |
| CircularBendingProcess | 34 | Použít k zobrazení dlouhé nebo nelineární sekvence kroků v úkolu, procesu nebo workflow. Nejlépe funguje pouze s textem úrovně 1. Maximalizuje jak vodorovný, tak svislý prostor pro zobrazení tvarů. |
| CircularPictureCallout | 35 | Použít k zobrazení centrální myšlenky a podmyšlenek nebo souvisejících položek. Text pro první obrázek pokrývá spodní část obrázku. Odpovídající text pro další tvary úrovně 1 se zobrazuje vedle malých kruhových obrázků. Tento diagram také dobře funguje bez textu. |
| ClosedChevronProcess | 36 | Použít k zobrazení postupu, časové osy nebo sekvenčních kroků v úkolu, procesu nebo workflow, nebo k zdůraznění pohybu či směru. Lze použít k zdůraznění informací v počátečním tvaru. Nejlépe funguje pouze s textem úrovně 1. |
| ContinuousArrowProcess | 37 | Použít k zobrazení časové osy nebo sekvenčních kroků v úkolu, procesu nebo workflow. Nejlépe funguje s textem úrovně 1, protože každý řádek textu úrovně 1 se zobrazuje uvnitř tvaru šipky. Text úrovně 2 se zobrazuje mimo tvar šipky. |
| ContinuousBlockProcess | 38 | Použít k zobrazení postupu nebo sekvenčních kroků v úkolu, procesu nebo workflow. Nejlépe funguje s minimálním množstvím textu úrovně 1 a úrovně 2. |
| ContinuousCycle | 39 | Použít k reprezentaci pokračující sekvence fází, úkolů nebo událostí v kruhovém toku. Zdůrazňuje propojení mezi všemi komponentami. Nejlépe funguje pouze s textem úrovně 1. |
| ContinuousPictureList | 40 | Použít k zobrazení skupin propojených informací. Kruhové tvary jsou navrženy tak, aby obsahovaly obrázky. |
| ConvergingArrows | 41 | Použít k zobrazení nápadů nebo konceptů, které se sbíhají do centrálního bodu. Nejlépe funguje pouze s textem úrovně 1. |
| ConvergingRadial | 42 | Použít k zobrazení vztahů konceptů nebo komponent k centrální myšlence v cyklu. První řádek textu úrovně 1 odpovídá centrálnímu kruhovému tvaru a řádky textu úrovně 2 odpovídají okolním obdélníkovým tvarům. Nepoužitý text se nezobrazí, ale zůstane k dispozici při změně rozvržení. |
| CounterbalanceArrows | 43 | Použít k zobrazení dvou protichůdných nápadů nebo konceptů. Každý z prvních dvou řádků textu úrovně 1 odpovídá šipce a dobře funguje s textem úrovně 2. Nepoužitý text se nezobrazí, ale zůstane k dispozici při změně rozvržení. |
| CycleMatrix | 44 | Použít k zobrazení vztahu k centrální myšlence v cyklickém postupu. Každý z prvních čtyř řádků textu úrovně 1 odpovídá segmentu nebo tvaru koláče a text úrovně 2 se zobrazuje v obdélníkovém tvaru na straně segmentu nebo tvaru koláče. Nepoužitý text se nezobrazí, ale zůstane k dispozici při změně rozvržení. |
| DescendingBlockList | 45 | Použít k zobrazení skupin souvisejících nápadů nebo seznamů informací. Textové tvary se sekvenčně snižují výškově a text úrovně 1 se zobrazuje vertikálně. |
| DescendingProcess | 46 | Použít k zobrazení sestupné série událostí. První text úrovně 1 je nahoře šipky a poslední text úrovně 1 se zobrazuje dole na šipce. Zobrazuje se pouze prvních sedm položek úrovně 1. Nejlépe funguje s malým až středním množstvím textu. |
| DetailedProcess | 47 | Použít s velkým množstvím textu úrovně 2 k zobrazení postupu fázemi. |
| DivergingArrows | 48 | Použít k zobrazení nápadů nebo konceptů, které vycházejí z centrálního zdroje. Nejlépe funguje pouze s textem úrovně 1. |
| DivergingRadial | 49 | Použít k zobrazení vztahů k centrální myšlence v cyklu. První řádek textu úrovně 1 odpovídá centrálnímu kruhovému tvaru. Zdůrazňuje okolní kruhy spíše než centrální myšlenku. Nepoužitý text se nezobrazí, ale zůstane k dispozici při změně rozvržení. |
| Equation | 50 | Použít k zobrazení sekvenčních kroků nebo úkolů, které znázorňují plán nebo výsledek. Poslední řádek textu úrovně 1 se objeví za rovnítkem (=). Nejlépe funguje pouze s textem úrovně 1. |
| FramedTextPicture | 51 | Použít k zobrazení obrázků s odpovídajícím textem úrovně 1 zobrazeným v rámečku. |
| Funnel | 52 | Použít k zobrazení filtrování informací nebo toho, jak se části spojují do celku. Zdůrazňuje konečný výsledek. Může obsahovat až čtyři řádky textu úrovně 1; poslední z těchto čtyř řádků textu úrovně 1 se objeví pod trychtýřem a ostatní řádky odpovídají kruhovému tvaru. Nepoužitý text se nezobrazí, ale zůstane k dispozici při změně rozvržení. |
| Gear | 53 | Použít k zobrazení propojených nápadů. Každý z prvních tří řádků textu úrovně 1 odpovídá tvaru ozubeného kola a jejich odpovídající text úrovně 2 se zobrazuje v obdélnících vedle tvaru ozubeného kola. Nepoužitý text se nezobrazí, ale zůstane k dispozici při změně rozvržení. |
| GridMatrix | 54 | Použijte k zobrazení umístění konceptů podél dvou os. Zdůrazňuje jednotlivé komponenty spíše než celek. První čtyři řádky textu úrovně 1 se zobrazí v kvadrantech. Nepoužitý text se nezobrazí, ale zůstane k dispozici, pokud přepnete rozvržení. |
| GroupedList | 55 | Použijte k zobrazení skupin a podskupin informací nebo kroků a podkroků v úkolu, procesu nebo pracovním postupu. Text úrovně 1 odpovídá horním horizontálním tvarům a text úrovně 2 odpovídá vertikálním podkrokům pod každým souvisejícím horním tvarem. Hodí se k zdůraznění podskupin nebo podkroků, hierarchických informací nebo více seznamů informací. |
| HalfCircleOrganizationChart | 56 | Použijte k zobrazení hierarchických informací nebo vztahů podřízenosti v organizaci. Pomocné tvary a Org Chart hanging layouts jsou k dispozici s tímto rozvržením. |
| HexagonCluster | 57 | Použijte k zobrazení obrázků s přidruženým popisným textem. Malé šestiúhelníky označují dvojici obrázek-text. Funguje nejlépe při malém množství textu. |
| Hierarchy | 58 | Použijte k zobrazení hierarchických vztahů postupujících od shora dolů. |
| HierarchyList | 59 | Použijte k zobrazení hierarchických vztahů postupujících napříč skupinami. Lze také použít k seskupení nebo vyjmenování informací. |
| HorizontalBulletList | 60 | Použijte k zobrazení nesekvenčních nebo seskupených seznamů informací. Funguje dobře při velkém množství textu. Veškerý text má stejnou úroveň důrazu a směr není naznačen. |
| HorizontalHierarchy | 61 | Použijte k zobrazení hierarchických vztahů postupujících vodorovně. Hodí se pro rozhodovací stromy. |
| HorizontalLabeledHierarchy | 62 | Použijte k zobrazení hierarchických vztahů postupujících vodorovně a seskupených hierarchicky. Zdůrazňuje nadpis nebo text úrovně 1. První řádek textu úrovně 1 se zobrazí ve tvaru na začátku hierarchie a druhý a všechny následující řádky textu úrovně 1 se zobrazí na vrcholu vysokých obdélníků. |
| HorizontalMultiLevelHierarchy | 63 | Použijte k zobrazení velkého množství hierarchických informací postupujících vodorovně. Vrchol hierarchie je zobrazen vertikálně. Toto rozvržení podporuje mnoho úrovní v hierarchii. |
| HorizontalOrganizationChart | 64 | Použijte k zobrazení hierarchických informací vodorovně nebo vztahů podřízenosti v organizaci. Pomocný tvar a Org Chart hanging layouts jsou k dispozici s tímto rozvržením. |
| HorizontalPictureList | 65 | Použijte k zobrazení nesekvenčních nebo seskupených informací s důrazem na související obrázky. Horní tvary jsou navrženy tak, aby obsahovaly obrázky. |
| IncreasingArrowsProcess | 66 | Použijte k zobrazení sekvenčních a překrývajících se kroků v procesu. Omezeno na pět položek úrovně 1. Úroveň 2 může obsahovat velké množství textu. |
| IncreasingCircleProcess | 67 | Použijte k zobrazení série kroků, kdy vnitřek kruhu roste s každým krokem. Omezeno na sedm kroků úrovně 1, ale neomezený počet položek úrovně 2. Funguje dobře s velkým množstvím textu úrovně 2. |
| InvertedPyramid | 68 | Použijte k zobrazení proporčních, propojených nebo hierarchických vztahů s největší součástí nahoře a zužováním směrem dolů. Text úrovně 1 se zobrazuje v segmentech pyramidy a text úrovně 2 se zobrazuje ve tvarech podél každého segmentu. |
| LabeledHierarchy | 69 | Použijte k zobrazení hierarchických vztahů postupujících od shora dolů a seskupených hierarchicky. Zdůrazňuje nadpis nebo text úrovně 1. První řádek textu úrovně 1 se zobrazí ve tvaru na začátku hierarchie a všechny následující řádky textu úrovně 1 se zobrazí vlevo od dlouhých obdélníků. |
| LinearVenn | 70 | Použijte k zobrazení překrývajících se vztahů v sekvenci. Funguje nejlépe pouze s textem úrovně 1. |
| LinedList | 71 | Použijte k zobrazení velkého množství textu rozděleného do kategorií a podkategorií. Funguje dobře s více úrovněmi textu. Text na stejné úrovni je oddělen čarami. |
| MultidirectionalCycle | 72 | Použijte k znázornění pokračující sekvence fází, úkolů nebo událostí, které mohou nastat v libovolném směru. |
| NameandTitleOrganizationChart | 73 | Použijte k zobrazení hierarchických informací nebo vztahů podřízenosti v organizaci. Pro zadání textu do pole nadpisu pište přímo do menšího obdélníkového tvaru. Pomocný tvar a Org Chart hanging layouts jsou k dispozici s tímto rozvržením. |
| NestedTarget | 74 | Použijte k zobrazení vztahů obsahování. Každý z prvních tří řádků textu úrovně 1 odpovídá textu v levém horním rohu tvarů a text úrovně 2 odpovídá menším tvarům. Funguje nejlépe s minimálním množstvím řádků textu úrovně 2. Nepoužitý text se nezobrazí, ale zůstane k dispozici, pokud přepnete rozvržení. |
| NondirectionalCycle | 75 | Použijte k znázornění pokračující sekvence fází, úkolů nebo událostí v kruhovém toku. Každý tvar má stejnou úroveň důležitosti. Funguje dobře, když není nutné uvádět směr. |
| OpposingArrows | 76 | Použijte k zobrazení dvou protichůdných myšlenek nebo myšlenek, které se odchylují od centrálního bodu. Každý z prvních dvou řádků textu úrovně 1 odpovídá šipce. Nepoužitý text se nezobrazí, ale zůstane k dispozici, pokud přepnete rozvržení. |
| OpposingIdeas | 77 | Použijte k zobrazení dvou protichůdných nebo kontrastních myšlenek. Může obsahovat jednu nebo dvě položky úrovně 1. Každý text úrovně 1 může obsahovat více podúrovní. Funguje dobře s velkým množstvím textu. |
| OrganizationChart | 78 | Použijte k zobrazení hierarchických informací nebo vztahů podřízenosti v organizaci. Pomocný tvar a Org Chart hanging layouts jsou k dispozici s tímto rozvržením. |
| PhasedProcess | 79 | Použijte k zobrazení tří fází procesu. Omezeno na tři položky úrovně 1. První dvě položky úrovně 1 mohou každá obsahovat čtyři položky úrovně 2 a třetí položka úrovně 1 může obsahovat neomezený počet položek úrovně 2. Funguje nejlépe s malým množstvím textu. |
| PictureAccentBlocks | 80 | Použijte k zobrazení skupiny obrázků v blocích počínaje rohem. Příslušný text se zobrazuje svisle. Hodí se jako akcent na snímcích s titulkem nebo podtitulkem či pro oddělení sekcí dokumentu. |
| PictureAccentList | 81 | Použijte k zobrazení seskupených nebo souvisejících informací. Malé tvary v horních rozích jsou určeny k umístění obrázků. Zdůrazňuje text úrovně 2 nad textem úrovně 1 a je vhodnou volbou pro velké množství textu úrovně 2. |
| PictureAccentProcess | 82 | Použijte k zobrazení sekvenčních kroků v úkolu, procesu nebo pracovním postupu. Obdélníkové tvary v pozadí jsou určeny k umístění obrázků. |
| PictureCaptionList | 83 | Použijte k zobrazení nesekvenčních nebo seskupených bloků informací. Horní tvary jsou určeny k umístění obrázků a obrázky jsou zvýrazněny nad textem. Hodí se pro obrázky s krátkými popisky. |
| PictureGrid | 84 | Použijte k zobrazení obrázků uspořádaných do čtvercové mřížky. Nejlépe s malým množstvím textu úrovně 1, který se zobrazuje nad obrázkem. |
| PictureLineup | 85 | Použijte k zobrazení série obrázků vedle sebe. Text úrovně 1 pokrývá horní část obrázku. Text úrovně 2 se zobrazuje pod obrázkem. |
| PictureStrips | 86 | Použijte k zobrazení série obrázků shora dolů s textem úrovně 1 vedle každého. |
| PieProcess | 87 | Použijte k zobrazení kroků procesu, kde každý výsek koláče roste do velikosti až sedmi tvarů. Text úrovně 1 se zobrazuje svisle. |
| PlusandMinus | 88 | Použijte k zobrazení výhod a nevýhod dvou myšlenek. Každý text úrovně 1 může obsahovat více podúrovní. Funguje dobře s velkým množstvím textu. Omezeno na dvě položky úrovně 1. |
| ProcessArrows | 89 | Použijte k zobrazení informací ilustrujících proces nebo pracovní postup. Text úrovně 1 se zobrazuje v kruhových tvarech a text úrovně 2 v šipkových tvarech. Nejlépe pro minimální množství textu a zdůraznění pohybu nebo směru. |
| ProcessList | 90 | Použijte k zobrazení více skupin informací nebo kroků a podkroků v úkolu, procesu nebo pracovním postupu. Text úrovně 1 odpovídá horním horizontálním tvarem a text úrovně 2 odpovídá vertikálním podkrokům pod každým souvisejícím horním tvarem. |
| PyramidList | 91 | Použijte k zobrazení proporčních, propojených nebo hierarchických vztahů. Text se objevuje v obdélníkových tvarech na pozadí pyramidy. |
| RadialCluster | 92 | Použijte k zobrazení dat souvisejících se střední myšlenkou nebo tématem. Horní text úrovně 1 se zobrazuje uprostřed. Text úrovně 2 se zobrazuje v okolních tvarech. Může obsahovat až sedm tvarů úrovně 2. Nepoužitý text se nezobrazí, ale zůstane k dispozici, pokud přepnete rozvržení. Nejlépe s malým množstvím textu. |
| RadialCycle | 93 | Použijte k zobrazení vztahu ke střední myšlence. Zvýrazňuje informace jak ve středovém kruhu, tak to, jak informace v vnějším prstenci kruhů přispívají k centrální myšlence. První řádek textu úrovně 1 odpovídá středovému kruhu a jeho text úrovně 2 odpovídá vnějšímu prstenci kruhů. Nepoužitý text se nezobrazí, ale zůstane k dispozici, pokud přepnete rozvržení. |
| RadialList | 94 | Použijte k zobrazení vztahů ke střední myšlence v cyklu. Střední tvar může obsahovat obrázek. Text úrovně 1 se zobrazuje v menších kruzích a související text úrovně 2 se zobrazuje po straně menších kruhů. |
| RadialVenn | 95 | Použijte k zobrazení jak překrývajících se vztahů, tak vztahu ke střední myšlence v cyklu. První řádek textu úrovně 1 odpovídá centrálnímu tvaru a řádky textu úrovně 2 odpovídají okolním kruhovým tvarům. Nepoužitý text se nezobrazí, ale zůstane k dispozici, pokud přepnete rozvržení. |
| RandomToResultProcess | 96 | Použijte k zobrazení, jak série kroků může z několika chaotických myšlenek vést k jednotnému cíli nebo myšlence. Podporuje více položek textu úrovně 1, ale první a poslední tvar odpovídající úrovni 1 jsou pevné. Nejlépe s malým množstvím textu úrovně 1 a středním množstvím textu úrovně 2. |
| RepeatingBendingProcess | 97 | Použijte k zobrazení postupu nebo sekvenčních kroků v úkolu, procesu nebo pracovním postupu. Maximálně využívá vodorovný i svislý prostor pro tvary. |
| ReverseList | 98 | Použijte k přepínání mezi dvěma položkami. Zobrazí se jen první dva textové položky a každá položka může obsahovat velké množství textu. Hodí se k ukázání změny mezi dvěma položkami nebo posunu v pořadí. |
| SegmentedCycle | 99 | Použijte k zobrazení postupu nebo sekvence fází, úkolů nebo událostí v kruhovém toku. Zdůrazňuje propojené části. Každý z prvních sedmi řádků textu úrovně 1 odpovídá výseči nebo tvaru koláče. Nepoužitý text se nezobrazí, ale zůstane k dispozici, pokud přepnete rozvržení. |
| SegmentedProcess | 100 | Použijte k zobrazení postupu nebo sekvenčních kroků v úkolu, procesu nebo pracovním postupu. Zdůrazňuje text úrovně 2, protože každý řádek se objevuje v samostatném tvaru. |
| SegmentedPyramid | 101 | Použijte k zobrazení vztahů obsahování, proporčních nebo propojených. Prvních devět řádků textu úrovně 1 se zobrazí v trojúhelníkových tvarech. Nepoužitý text se nezobrazí, ale zůstane k dispozici, pokud přepnete rozvržení. Nejlépe pouze s textem úrovně 1. |
| SnapshotPictureList | 102 | Použijte k zobrazení obrázků s vysvětlujícím textem. Text úrovně 2 může zobrazovat seznamy informací. Hodí se pro velké množství textu. |
| SpiralPicture | 103 | Použijte k zobrazení série až pěti obrázků s odpovídajícími titulky úrovně 1, které se spirálovitě stáčejí do středu. |
| SquareAccentList | 104 | Použijte k zobrazení seznamů informací rozdělených do kategorií. Text úrovně 2 se objevuje vedle malého čtvercového tvaru. Hodí se pro velké množství textu úrovně 2. |
| StackedList | 105 | Použijte k zobrazení skupin informací nebo kroků v úkolu, procesu nebo pracovním postupu. Kruhové tvary obsahují text úrovně 1 a odpovídající obdélníky obsahují text úrovně 2. Hodí se pro mnoho detailů a minimální text úrovně 1. |
| StackedVenn | 106 | Použijte k zobrazení překrývajících se vztahů. Dobrá volba pro zdůraznění růstu nebo gradace. Nejlépe s pouze textem úrovně 1. Prvních sedm řádků textu úrovně 1 odpovídá kruhovému tvaru. Nepoužitý text se nezobrazí, ale zůstane k dispozici, pokud přepnete rozvržení. |
| StaggeredProcess | 107 | Použijte k zobrazení sestupného postupu skrze fáze. Každá z prvních pěti řádků textu úrovně 1 odpovídá obdélníku. Nepoužitý text se nezobrazí, ale zůstane k dispozici, pokud přepnete rozvržení. |
| StepDownProcess | 108 | Použijte k zobrazení klesajícího procesu s několika kroky a podkroky. Funguje nejlépe s malým množstvím textu. |
| StepUpProcess | 109 | Použijte k zobrazení vzestupné řady kroků nebo seznamů informací. |
| SubStepProcess | 110 | Použijte k zobrazení vícekrokového procesu s podkroky mezi jednotlivými výskyty textu úrovně 1. Funguje nejlépe s malým množstvím textu a je omezen na sedm kroků úrovně 1. Každý krok úrovně 1 může mít neomezený počet podkroků. |
| TableHierarchy | 111 | Použijte k zobrazení skupin informací vytvořených shora dolů a hierarchií v každé skupině. Toto rozvržení neobsahuje spojovací čáry. |
| TableList | 112 | Použijte k zobrazení seskupených nebo souvisejících informací stejné hodnoty. První řádek textu úrovně 1 odpovídá hornímu tvaru a jeho text úrovně 2 se používá pro následující seznamy. |
| TargetList | 113 | Použijte k zobrazení vzájemně souvisejících nebo překrývajících se informací. Každý z prvních sedmi řádků textu úrovně 1 se zobrazí v obdélníkovém tvaru. Nepoužitý text se nezobrazí, ale zůstane k dispozici, pokud přepnete rozvržení. Dobře funguje jak s textem úrovně 1, tak úrovně 2. |
| TextCycle | 114 | Použijte k reprezentaci pokračující sekvence fází, úkolů nebo událostí v kruhovém toku. Zdůrazňuje šipky nebo tok spíše než fáze či kroky. Funguje nejlépe pouze s textem úrovně 1. |
| TitlePictureLineup | 115 | Použijte k zobrazení řady obrázků, z nichž každý má svůj vlastní název a popis. Text úrovně 1 se zobrazuje v rámečku nad obrázkem. Text úrovně 2 se zobrazuje pod obrázkem. |
| TitledMatrix | 116 | Použijte k zobrazení vztahů čtyř kvadrantů k celku. První řádek textu úrovně 1 odpovídá centrálnímu tvaru a první čtyři řádky textu úrovně 2 se zobrazí v kvadrantech. Nepoužitý text se nezobrazí, ale zůstane k dispozici, pokud přepnete rozvržení. |
| TitledPictureAccentList | 117 | Použijte k zobrazení seznamů informací s akcentním obrázkem pro každý text úrovně 2. Text úrovně 1 se zobrazí v samostatném rámečku na vrcholu seznamu. |
| TitledPictureBlocks | 118 | Použijte k zobrazení řady obrázků. Text úrovně 1 se zobrazuje nad každým obrázkem. Text úrovně 2 se zobrazuje po straně a mírně překrývá každý obrázek. |
| TrapezoidList | 119 | Použijte k zobrazení seskupených nebo souvisejících informací stejné hodnoty. Funguje dobře s velkým množstvím textu. |
| UpwardArrow | 120 | Použijte k zobrazení postupu nebo kroků, které směřují vzhůru v úkolu, procesu nebo pracovním postupu. Každý z prvních pěti řádků textu úrovně 1 odpovídá bodu na šípku. Funguje nejlépe s minimálním množstvím textu. Nepoužitý text se nezobrazí, ale zůstane k dispozici, pokud přepnete rozvržení. |
| VerticalAccentList | 121 | Použijte k zobrazení seznamů informací. Text úrovně 2 se zobrazuje v obdélníkových tvarech nad svislými šipkami. Zdůrazňuje text úrovně 2 před textem úrovně 1 a je vhodnou volbou pro střední množství textu úrovně 2. |
| VerticalArrowList | 122 | Použijte k zobrazení postupu nebo sekvenčních kroků v úkolu, procesu nebo pracovním postupu, které směřují k společnému cíli. Dobře funguje pro odrážkové seznamy informací. |
| VerticalBendingProcess | 123 | Použijte k zobrazení postupu nebo sekvenčních kroků v úkolu, procesu nebo pracovním postupu. Maximálně využívá jak vodorovný, tak svislý prostor pro tvary. Klade větší důraz na vzájemné vztahy mezi tvary než na směr nebo pohyb. |
| VerticalBlockList | 124 | Použijte k zobrazení skupin informací nebo kroků v úkolu, procesu nebo pracovním postupu. Funguje dobře s velkým množstvím textu úrovně 2. Je vhodnou volbou pro text s hlavním bodem a více podbody. |
| VerticalBoxList | 125 | Použijte k zobrazení několika skupin informací, zejména skupin s velkým množstvím textu úrovně 2. Je vhodnou volbou pro odrážkové seznamy informací. |
| VerticalBulletList | 126 | Použijte k zobrazení nesekvenčních nebo seskupených bloků informací. Dobře funguje pro seznamy s dlouhými nadpisy nebo informacemi nejvyšší úrovně. |
| VerticalChevronList | 127 | Použijte k zobrazení postupu nebo sekvenčních kroků v úkolu, procesu nebo pracovním postupu, nebo k zdůraznění pohybu či směru. Zdůrazňuje text úrovně 2 před textem úrovně 1 a je vhodnou volbou pro velké množství textu úrovně 2. |
| VerticalCircleList | 128 | Použijte k zobrazení sekvenčních nebo seskupených dat. Nejlépe funguje pro text úrovně 1, který se zobrazuje vedle velkého kruhového tvaru. Nižší úrovně textu jsou odděleny menšími kruhovými tvary. |
| VerticalCurvedList | 129 | Použijte k zobrazení zakřiveného seznamu informací. Pro přidání obrázků do akcentovaných kruhových tvarů použijte výplň obrázkem. |
| VerticalEquation | 130 | Použijte k zobrazení sekvenčních kroků nebo úkolů, které znázorňují plán nebo výsledek. Poslední řádek textu úrovně 1 se zobrazí za šípkou. Nejlépe funguje pouze s textem úrovně 1. |
| VerticalPictureAccentList | 131 | Použijte k zobrazení nesekvenčních nebo seskupených bloků informací. Malé kruhy jsou navrženy tak, aby obsahovaly obrázky. |
| VerticalPictureList | 132 | Použijte k zobrazení nesekvenčních nebo seskupených bloků informací. Malé tvary vlevo jsou navrženy tak, aby obsahovaly obrázky. |
| VerticalProcess | 133 | Použijte k zobrazení postupu nebo sekvenčních kroků v úkolu, procesu nebo pracovním postupu shora dolů. Nejlépe funguje s textem úrovně 1, protože svislý prostor je omezený. |
| Custom | 134 | Reprezentuje diagram [SmartArt](../smartart/) s vlastním rozvržením šablony |
| PictureOrganizationChart | 135 | Použijte k zobrazení hierarchických informací nebo vztahů podřízenosti v organizaci, s odpovídajícími obrázky. Asistentský tvar a rozložení Org Chart hanging jsou s tímto rozvržením k dispozici. |

## Viz také

* Jmenný prostor [Aspose::Slides::SmartArt](../)
* Knihovna [Aspose.Slides](../../)