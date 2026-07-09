---
title: SmartArtLayoutType
second_title: Aspose.Sildes pro .NET - referenční příručka API
description: Reprezentuje typ rozvržení SmartArt diagramu.
type: docs
weight: 10620
url: /cs/aspose.slides.smartart/smartartlayouttype/
---
## Enumerace SmartArtLayoutType

Reprezentuje typ rozvržení diagramu SmartArt.

```csharp
public enum SmartArtLayoutType
```

### Hodnoty

| Název | Hodnota | Popis |
| --- | --- | --- |
| AccentProcess | `0` | Používá se k zobrazení postupného vývoje, časové osy nebo sekvenčních kroků v úkolu, procesu nebo pracovním postupu. Dobře funguje při ilustraci textu úrovně 1 i úrovně 2. |
| AccentedPicture | `1` | Používá se k zobrazení centrální fotografické myšlenky s souvisejícími nápady po stranách. Horní text úrovně 1 se zobrazuje nad centrálním obrázkem. Odpovídající text pro ostatní tvary úrovně 1 se zobrazuje vedle malých kruhových obrázků. Tento rozvržení také dobře funguje bez textu. |
| AlternatingFlow | `2` | Používá se k zobrazení skupin informací nebo sekvenčních kroků v úkolu, procesu nebo pracovním postupu. Zdůrazňuje interakci nebo vztahy mezi skupinami informací. |
| AlternatingHexagons | `3` | Používá se k zobrazení řady propojených nápadů. Text úrovně 1 se zobrazí uvnitř hexagonů. Text úrovně 2 se zobrazí mimo tvary. |
| AlternatingPictureBlocks | `4` | Používá se k zobrazení řady obrázků shora dolů. Text se střídavě objevuje vpravo nebo vlevo od obrázku. |
| AlternatingPictureCircles | `5` | Používá se k zobrazení sady obrázků s textem. Odpovídající text se objeví ve středových kruzích, přičemž obrázky se střídají zleva doprava. |
| ArrowRibbon | `6` | Používá se k zobrazení souvisejících nebo kontrastních konceptů s určitým propojením, např. protichůdných sil. První dva řádky textu úrovně 1 se používají pro text v šipkách. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozvržení. |
| AscendingPictureAccentProcess | `7` | Používá se k zobrazení vzestupné řady obrázků s popisným textem. Nejlépe funguje při malém množství textu. |
| Balance | `8` | Používá se k porovnání nebo zobrazení vztahu mezi dvěma nápady. Každý z prvních dvou řádků textu úrovně 1 odpovídá textu nahoře na jedné straně středového bodu. Zdůrazňuje text úrovně 2, který je omezen na čtyři tvary na každé straně středového bodu. Vyvážení se nakloní ke straně s nejvíce tvary obsahujícími text úrovně 2. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozvržení. |
| BasicBendingProcess | `9` | Používá se k zobrazení postupného vývoje nebo sekvenčních kroků v úkolu, procesu nebo pracovním postupu. Maximalizuje jak vodorovný, tak svislý prostor pro tvary. |
| BasicBlockList | `10` | Používá se k zobrazení netradičních nebo seskupených bloků informací. Maximalizuje vodorovný i svislý prostor pro tvary. |
| BasicChevronProcess | `11` | Používá se k zobrazení postupu; časové osy; sekvenčních kroků v úkolu, procesu nebo pracovním postupu; nebo k zdůraznění pohybu či směru. Text úrovně 1 se zobrazuje uvnitř šipkového tvaru, zatímco text úrovně 2 se zobrazuje pod šipkovými tvary. |
| BasicCycle | `12` | Používá se k reprezentaci kontinuální posloupnosti fází, úkolů nebo událostí v kruhovém toku. Zdůrazňuje fáze nebo kroky spíše než propojující šipky či tok. Nejlépe funguje pouze s textem úrovně 1. |
| BasicMatrix | `13` | Používá se k zobrazení vztahu komponent k celku v kvadrantech. První čtyři řádky textu úrovně 1 se zobrazí v kvadrantech. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozvržení. |
| BasicPie | `14` | Používá se k zobrazení, jak jednotlivé části tvoří celek. Prvních sedm řádků textu úrovně 1 odpovídá rovnoměrně rozděleným výsečím nebo koláčovým tvarům. Horní tvar textu úrovně 1 se zobrazuje mimo zbytek koláče pro zdůraznění. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozvržení. |
| BasicProcess | `15` | Používá se k zobrazení postupu nebo sekvenčních kroků v úkolu, procesu nebo pracovním postupu. |
| BasicPyramid | `16` | Používá se k zobrazení poměrných, propojených nebo hierarchických vztahů s největší komponentou dole a zužováním směrem nahoru. Text úrovně 1 se objevuje v segmentech pyramidy a text úrovně 2 v tvarech podél každého segmentu. |
| BasicRadial | `17` | Používá se k zobrazení vztahu k centrální myšlence v cyklu. První řádek textu úrovně 1 odpovídá centrálnímu tvaru a jeho text úrovně 2 odpovídá okolním kruhovým tvarům. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozvržení. |
| BasicTarget | `18` | Používá se k zobrazení obsahu, stupňování nebo hierarchických vztahů. Prvních pět řádků textu úrovně 1 je spojeno s kruhem. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozvržení. |
| BasicTimeline | `19` | Používá se k zobrazení sekvenčních kroků v úkolu, procesu nebo pracovním postupu nebo k zobrazení informací o časové ose. Dobře funguje s textem úrovně 1 i úrovně 2. |
| BasicVenn | `20` | Používá se k zobrazení překrývajících se nebo propojených vztahů. Prvních sedm řádků textu úrovně 1 odpovídá kruhu. Pokud je čtyři nebo méně řádků textu úrovně 1, text je uvnitř kruhů. Pokud je více než čtyři řádky, text je mimo kruhy. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozvržení. |
| BendingPictureAccentList | `21` | Používá se k zobrazení netradičních nebo seskupených bloků informací. Malé kruhové tvary jsou určeny k umístění obrázků. Dobře ilustruje text úrovně 1 i úrovně 2. Maximalizuje vodorovný i svislý prostor pro tvary. |
| BendingPictureBlocks | `22` | Používá se k zobrazení řady obrázků. Box v dolním rohu může obsahovat malé množství textu. |
| BendingPictureCaption | `23` | Používá se k zobrazení sekvenční řady obrázků. Box v dolním rohu může obsahovat malé množství textu. |
| BendingPictureCaptionList | `24` | Používá se k zobrazení řady obrázků. Název a popis se zobrazí v bublinovém tvaru pod každým obrázkem. |
| BendingPictureSemiTransparentText | `25` | Používá se k zobrazení řady obrázků. Poloprůhledný box pokrývá spodní část obrázku a obsahuje všechny úrovně textu. |
| BlockCycle | `26` | Používá se k reprezentaci kontinuální posloupnosti fází, úkolů nebo událostí v kruhovém toku. Zdůrazňuje fáze nebo kroky spíše než propojující šipky či tok. |
| BubblePictureList | `27` | Používá se k zobrazení řady obrázků. Může obsahovat až osm obrázků úrovně 1. Nepoužitý text a obrázky se nezobrazí, ale zůstávají k dispozici při změně rozvržení. Nejlépe funguje s malým množstvím textu. |
| CaptionedPictures | `28` | Používá se k zobrazení obrázků s více úrovněmi textu. Nejlépe funguje s malým množstvím textu úrovně 1 a středním množstvím textu úrovně 2. |
| ChevronList | `29` | Používá se k zobrazení postupu přes několik procesů, které tvoří celkový pracovní postup. Také slouží k ilustraci kontrastních procesů. Text úrovně 1 odpovídá první šipce vlevo, zatímco text úrovně 2 odpovídá horizontálním podkrokům pro každý tvar, který obsahuje text úrovně 1. |
| CircleAccentTimeline | `30` | Používá se k zobrazení řady událostí nebo informací o časové ose. Text úrovně 1 se zobrazuje vedle větších kruhových tvarů. Text úrovně 2 se zobrazuje vedle menších kruhových tvarů. |
| CircleArrowProcess | `31` | Používá se k zobrazení sekvenčních položek s doprovodným textem pro každou položku. Tento diagram nejlépe funguje s malým množstvím textu úrovně 1. |
| CirclePictureHierarchy | `32` | Používá se k zobrazení hierarchických informací nebo vztahů podřízenosti v organizaci. Obrázky se zobrazují v kruzích a odpovídající text vedle obrázků. |
| CircleRelationship | `33` | Používá se k zobrazení vztahu k centrální myšlence nebo od ní. Text úrovně 2 se přidává netradičně a je omezen na pět položek. Může existovat pouze jedna položka úrovně 1. |
| CircularBendingProcess | `34` | Používá se k zobrazení dlouhé nebo nelineární posloupnosti či kroků v úkolu, procesu nebo pracovním postupu. Nejlépe funguje pouze s textem úrovně 1. Maximalizuje vodorovný i svislý prostor pro tvary. |
| CircularPictureCallout | `35` | Používá se k zobrazení centrální myšlenky a podmyšlenek nebo souvisejících položek. Text pro první obrázek pokrývá spodní část obrázku. Odpovídající text pro ostatní tvary úrovně 1 se zobrazuje vedle malých kruhových obrázků. Tento diagram také dobře funguje bez textu. |
| ClosedChevronProcess | `36` | Používá se k zobrazení postupu, časové osy nebo sekvenčních kroků v úkolu, procesu nebo pracovním postupu, nebo k zdůraznění pohybu či směru. Lze použít k zdůraznění informací v úvodním tvaru. Nejlépe funguje pouze s textem úrovně 1. |
| ContinuousArrowProcess | `37` | Používá se k zobrazení časové osy nebo sekvenčních kroků v úkolu, procesu nebo pracovním postupu. Nejlépe funguje s textem úrovně 1, protože každý řádek textu úrovně 1 se zobrazuje uvnitř šipkového tvaru. Text úrovně 2 se zobrazuje mimo šipkový tvar. |
| ContinuousBlockProcess | `38` | Používá se k zobrazení postupu nebo sekvenčních kroků v úkolu, procesu nebo pracovním postupu. Nejlépe funguje s minimálním množstvím textu úrovně 1 i 2. |
| ContinuousCycle | `39` | Používá se k reprezentaci kontinuální posloupnosti fází, úkolů nebo událostí v kruhovém toku. Zdůrazňuje spojení mezi všemi komponentami. Nejlépe funguje pouze s textem úrovně 1. |
| ContinuousPictureList | `40` | Používá se k zobrazení skupin propojených informací. Kružkové tvary jsou určeny k umístění obrázků. |
| ConvergingArrows | `41` | Používá se k zobrazení myšlenek nebo konceptů, které konvergují do centrálního bodu. Nejlépe funguje pouze s textem úrovně 1. |
| ConvergingRadial | `42` | Používá se k zobrazení vztahů konceptů nebo komponent k centrální myšlence v cyklu. První řádek textu úrovně 1 odpovídá centrálnímu kruhovému tvaru a řádky textu úrovně 2 odpovídají okolním obdélníkovým tvarům. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozvržení. |
| CounterbalanceArrows | `43` | Používá se k zobrazení dvou protichůdných myšlenek nebo konceptů. Každý z prvních dvou řádků textu úrovně 1 odpovídá šipce a dobře funguje s textem úrovně 2. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozvržení. |
| CycleMatrix | `44` | Používá se k zobrazení vztahu k centrální myšlence v cyklickém postupu. Každý z prvních čtyř řádků textu úrovně 1 odpovídá výseč nebo koláčovému tvaru a text úrovně 2 se zobrazuje v obdélníkovém tvaru po straně výseče nebo koláčového tvaru. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozvržení. |
| DescendingBlockList | `45` | Používá se k zobrazení skupin souvisejících nápadů nebo seznamů informací. Textové tvary se sekvenčně zmenšují výškou a text úrovně 1 se zobrazuje vertikálně. |
| DescendingProcess | `46` | Používá se k zobrazení sestupné řady událostí. První text úrovně 1 je na vrcholu šipky a poslední text úrovně 1 se zobrazuje na spodku šipky. Zobrazí se pouze prvních sedm položek úrovně 1. Nejlépe funguje s malým až středním množstvím textu. |
| DetailedProcess | `47` | Používá se s velkým množstvím textu úrovně 2 k zobrazení postupu skrze fáze. |
| DivergingArrows | `48` | Používá se k zobrazení nápadů nebo konceptů, které se rozšiřují od centrálního zdroje. Nejlépe funguje pouze s textem úrovně 1. |
| DivergingRadial | `49` | Používá se k zobrazení vztahů k centrální myšlence v cyklu. První řádek textu úrovně 1 odpovídá centrálnímu kruhovému tvaru. Zdůrazňuje okolní kruhy spíše než centrální myšlenku. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozvržení. |
| Equation | `50` | Používá se k zobrazení sekvenčních kroků nebo úkolů, které představují plán nebo výsledek. Poslední řádek textu úrovně 1 se zobrazí za znaménkem rovnosti (=). Nejlépe funguje pouze s textem úrovně 1. |
| FramedTextPicture | `51` | Používá se k zobrazení obrázků s odpovídajícím textem úrovně 1 zobrazeným v rámečku. |
| Funnel | `52` | Používá se k zobrazení filtrování informací nebo toho, jak se části spojují do celku. Zdůrazňuje konečný výsledek. Může obsahovat až čtyři řádky textu úrovně 1; poslední z těchto čtyř řádků se zobrazí pod trychtýřem a ostatní řádky odpovídají kruhovému tvaru. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozvržení. |
| Gear | `53` | Používá se k zobrazení zapadajících do sebe myšlenek. Každý z prvních tří řádků textu úrovně 1 odpovídá tvaru ozubeného kola a jejich odpovídající text úrovně 2 se zobrazuje v obdélnících vedle tvaru kola. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozvržení. |
| GridMatrix | `54` | Používá se k zobrazení umístění konceptů podél dvou os. Zdůrazňuje jednotlivé komponenty spíše než celek. První čtyři řádky textu úrovně 1 se zobrazí v kvadrantech. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozvržení. |
| GroupedList | `55` | Používá se k zobrazení skupin a podskupin informací nebo kroků a podkroků v úkolu, procesu nebo pracovním postupu. Text úrovně 1 odpovídá vodorovným tvarům nejvyšší úrovně a text úrovně 2 odpovídá svislým podkrokům pod každým souvisejícím tvarem nejvyšší úrovně. Dobře funguje při zdůrazňování podskupin nebo podkroků, hierarchických informací nebo několika seznamů informací. |
| HalfCircleOrganizationChart | `56` | Používá se k zobrazení hierarchických informací nebo vztahů podřízenosti v organizaci. Pomocné tvary a visící rozvržení organigramu jsou k dispozici s tímto rozvržením. |
| HexagonCluster | `57` | Používá se k zobrazení obrázků s přidruženým popisným textem. Malé hexagony označují pár obrázek-text. Nejlépe funguje s malým množstvím textu. |
| Hierarchy | `58` | Používá se k zobrazení hierarchických vztahů postupujících odshora dolů. |
| HierarchyList | `59` | Používá se k zobrazení hierarchických vztahů postupujících napříč skupinami. Lze také použít k seskupení nebo výčtu informací. |
| HorizontalBulletList | `60` | Používá se k zobrazení netradičních nebo seskupených seznamů informací. Dobře funguje s velkým množstvím textu. Veškerý text má stejnou úroveň důrazu a není naznačena žádná směrnost. |
| HorizontalHierarchy | `61` | Používá se k zobrazení hierarchických vztahů postupujících vodorovně. Dobře funguje pro rozhodovací stromy. |
| HorizontalLabeledHierarchy | `62` | Používá se k zobrazení hierarchických vztahů postupujících vodorovně a seskupených hierarchicky. Zdůrazňuje nadpis nebo text úrovně 1. První řádek textu úrovně 1 se zobrazí v tvaru na začátku hierarchie a druhý a všechny následující řádky textu úrovně 1 se zobrazí v horní části vysokých obdélníků. |
| HorizontalMultiLevelHierarchy | `63` | Používá se k zobrazení velkého množství hierarchických informací postupujících vodorovně. Horní část hierarchie je zobrazena vertikálně. Toto rozvržení podporuje mnoho úrovní v hierarchii. |
| HorizontalOrganizationChart | `64` | Používá se k zobrazení hierarchických informací vodorovně nebo vztahů podřízenosti v organizaci. Pomocný tvar a visící rozvržení organigramu jsou k dispozici s tímto rozvržením. |
| HorizontalPictureList | `65` | Používá se k zobrazení netradičních nebo seskupených informací s důrazem na související obrázky. Horní tvary jsou určeny k umístění obrázků. |
| IncreasingArrowsProcess | `66` | Používá se k zobrazení sekvenčních a překrývajících se kroků v procesu. Omezeno na pět položek úrovně 1. Úroveň 2 může obsahovat velké množství textu. |
| IncreasingCircleProcess | `67` | Používá se k zobrazení řady kroků, přičemž vnitřek kruhu se zvětšuje s každým krokem. Omezeno na sedm kroků úrovně 1, ale neomezený počet položek úrovně 2. Dobře funguje s velkým množstvím textu úrovně 2. |
| InvertedPyramid | `68` | Používá se k zobrazení poměrných, propojených nebo hierarchických vztahů s největší komponentou nahoře a zužováním dolů. Text úrovně 1 se objevuje v segmentech pyramidy a text úrovně 2 ve tvarech podél každého segmentu. |
| LabeledHierarchy | `69` | Používá se k zobrazení hierarchických vztahů postupujících shora dolů a seskupených hierarchicky. Zdůrazňuje nadpis nebo text úrovně 1. První řádek textu úrovně 1 se zobrazí v tvaru na začátku hierarchie a všechny následující řádky textu úrovně 1 se zobrazí vlevo od dlouhých obdélníků. |
| LinearVenn | `70` | Používá se k zobrazení překrývajících se vztahů v sekvenci. Nejlépe funguje pouze s textem úrovně 1. |
| LinedList | `71` | Používá se k zobrazení velkého množství textu rozděleného do kategorií a podkategorií. Dobře funguje s více úrovněmi textu. Text na stejné úrovni je oddělen čarami. |
| MultidirectionalCycle | `72` | Používá se k reprezentaci kontinuální posloupnosti fází, úkolů nebo událostí, které mohou nastat v libovolném směru. |
| NameandTitleOrganizationChart | `73` | Používá se k zobrazení hierarchických informací nebo vztahů podřízenosti v organizaci. Pro zadání textu do titulkového pole napište přímo do menšího obdélníkového tvaru. Pomocný tvar a visící rozvržení organigramu jsou k dispozici s tímto rozvržením. |
| NestedTarget | `74` | Používá se k zobrazení vztahů obsahu. Každý z prvních tří řádků textu úrovně 1 odpovídá levému hornímu textu ve tvarech a text úrovně 2 odpovídá menším tvarům. Nejlépe funguje s minimálním počtem řádků textu úrovně 2. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozvržení. |
| NondirectionalCycle | `75` | Používá se k reprezentaci kontinuální posloupnosti fází, úkolů nebo událostí v kruhovém toku. Každý tvar má stejnou úroveň důležitosti. Dobře funguje, když není potřeba uvádět směr. |
| OpposingArrows | `76` | Používá se k zobrazení dvou protichůdných nápadů nebo nápadů, které se odklánějí od centrálního bodu. Každý z prvních dvou řádků textu úrovně 1 odpovídá šipce. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozvržení. |
| OpposingIdeas | `77` | Používá se k zobrazení dvou protichůdných nebo kontrastních nápadů. Může mít jednu nebo dvě položky úrovně 1. Každý text úrovně 1 může obsahovat více podúrovní. Dobře funguje s velkým množstvím textu. |
| OrganizationChart | `78` | Používá se k zobrazení hierarchických informací nebo vztahů podřízenosti v organizaci. Pomocný tvar a visící rozvržení organigramu jsou k dispozici s tímto rozvržením. |
| PhasedProcess | `79` | Používá se k zobrazení tří fází procesu. Omezeno na tři položky úrovně 1. První dvě položky úrovně 1 mohou každá obsahovat čtyři položky úrovně 2 a třetí položka úrovně 1 může obsahovat neomezený počet položek úrovně 2. Nejlépe funguje s malým množstvím textu. |
| PictureAccentBlocks | `80` | Používá se k zobrazení skupiny obrázků v blocích vycházejících z rohu. Odpovídající text se zobrazuje vertikálně. Dobře funguje jako akcent na snímcích s titulkem nebo podtitulkem nebo pro oddílové přestávky v dokumentu. |
| PictureAccentList | `81` | Používá se k zobrazení seskupených nebo souvisejících informací. Malé tvary v horních rozích jsou určeny k umístění obrázků. Zdůrazňuje text úrovně 2 před textem úrovně 1 a je vhodný pro velké množství textu úrovně 2. |
| PictureAccentProcess | `82` | Používá se k zobrazení sekvenčních kroků v úkolu, procesu nebo pracovním postupu. Obdélníkové tvary v pozadí jsou určeny k umístění obrázků. |
| PictureCaptionList | `83` | Používá se k zobrazení netradičních nebo seskupených bloků informací. Horní tvary jsou určeny k umístění obrázků a obrázky jsou zdůrazněny před textem. Dobře funguje pro obrázky s krátkými textovými popisky. |
| PictureGrid | `84` | Používá se k zobrazení obrázků uspořádaných do čtvercové mřížky. Nejlépe s malým množstvím textu úrovně 1, který se zobrazí nad obrázkem. |
| PictureLineup | `85` | Používá se k zobrazení řady obrázků vedle sebe. Text úrovně 1 pokrývá horní část obrázku. Text úrovně 2 se zobrazí pod obrázkem. |
| PictureStrips | `86` | Používá se k zobrazení řady obrázků shora dolů s textem úrovně 1 vedle každého. |
| PieProcess | `87` | Používá se k zobrazení kroků v procesu, kde každá výseč koláče se zvětšuje až na sedm tvarů. Text úrovně 1 se zobrazí vertikálně. |
| PlusandMinus | `88` | Používá se k zobrazení výhod a nevýhod dvou nápadů. Každý text úrovně 1 může obsahovat více podúrovní. Dobře funguje s velkým množstvím textu. Omezeno na dvě položky úrovně 1. |
| ProcessArrows | `89` | Používá se k zobrazení informací ilustrujících proces nebo pracovní postup. Text úrovně 1 se zobrazí v kruhových tvarech a text úrovně 2 ve šipkových tvarech. Nejlépe pro minimální text a zdůraznění pohybu nebo směru. |
| ProcessList | `90` | Používá se k zobrazení více skupin informací nebo kroků a podkroků v úkolu, procesu nebo pracovním postupu. Text úrovně 1 odpovídá horizontálním tvarům nahoře a text úrovně 2 odpovídá svislým podkrokům pod každým souvisejícím tvarem nejvyšší úrovně. |
| PyramidList | `91` | Používá se k zobrazení poměrných, propojených nebo hierarchických vztahů. Text se zobrazuje v obdélníkových tvarech na vrcholu pozadí pyramidy. |
| RadialCluster | `92` | Používá se k zobrazení dat vztahujících se k centrální myšlence nebo tématu. Horní text úrovně 1 se zobrazí ve středu. Text úrovně 2 se zobrazí v okolních tvarech. Může obsahovat až sedm tvarů úrovně 2. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozvržení. Nejlépe s malým množstvím textu. |
| RadialCycle | `93` | Používá se k zobrazení vztahu k centrální myšlence. Zdůrazňuje jak informace ve středovém kruhu, tak jak informace v vnějším prstenci kruhů přispívají k centrální myšlence. První řádek textu úrovně 1 odpovídá středovému kruhu a jeho text úrovně 2 odpovídá vnějšímu prstenci kruhů. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozvržení. |
| RadialList | `94` | Používá se k zobrazení vztahů k centrální myšlenci v cyklu. Střední tvar může obsahovat obrázek. Text úrovně 1 se zobrazuje v menších kruzích a související text úrovně 2 se zobrazuje po boku menších kruhů. |
| RadialVenn | `95` | Používá se k zobrazení jak překrývajících se vztahů, tak vztahu k centrální myšlence v cyklu. První řádek textu úrovně 1 odpovídá centrálnímu tvaru a řádky textu úrovně 2 odpovídají okolním kruhovým tvarům. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozvržení. |
| RandomToResultProcess | `96` | Používá se k zobrazení, jak řadou kroků může několik chaotických nápadů vést k jednotnému cíli nebo myšlence. Podporuje více položek textu úrovně 1, ale první a poslední odpovídající tvary úrovně 1 jsou pevně dané. Nejlépe s malým množstvím textu úrovně 1 a středním množstvím textu úrovně 2. |
| RepeatingBendingProcess | `97` | Používá se k zobrazení postupu nebo sekvenčních kroků v úkolu, procesu nebo pracovním postupu. Maximalizuje vodorovný i svislý prostor pro tvary. |
| ReverseList | `98` | Používá se k přepínání mezi dvěma položkami. Zobrazí se pouze první dvě položky textu a každá položka může obsahovat velké množství textu. Dobře ukazuje změnu mezi dvěma položkami nebo posun v pořadí. |
| SegmentedCycle | `99` | Používá se k zobrazení postupu nebo sekvence fází, úkolů nebo událostí v kruhovém toku. Zdůrazňuje propojené části. Každý z prvních sedmi řádků textu úrovně 1 odpovídá výseči nebo koláčovému tvaru. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozvržení. |
| SegmentedProcess | `100` | Používá se k zobrazení postupu nebo sekvenčních kroků v úkolu, procesu nebo pracovním postupu. Zdůrazňuje text úrovně 2, protože každý řádek se zobrazí v samostatném tvaru. |
| SegmentedPyramid | `101` | Používá se k zobrazení vztahu obsahu, poměrných nebo propojených vztahů. Prvních devět řádků textu úrovně 1 se objevuje v trojúhelníkových tvarech. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozvržení. Nejlépe funguje pouze s textem úrovně 1. |
| SnapshotPictureList | `102` | Používá se k zobrazení obrázků s vysvětlujícím textem. Text úrovně 2 může zobrazovat seznamy informací. Dobře funguje s velkým množstvím textu. |
| SpiralPicture | `103` | Používá se k zobrazení řady až pěti obrázků s odpovídajícími popisky úrovně 1, které se spirálovitě vinou ke středu. |
| SquareAccentList | `104` | Používá se k zobrazení seznamů informací rozdělených do kategorií. Text úrovně 2 se objeví vedle malého čtvercového tvaru. Dobře funguje s velkým množstvím textu úrovně 2. |
| StackedList | `105` | Používá se k zobrazení skupin informací nebo kroků v úkolu, procesu nebo pracovním postupu. Kružkové tvary obsahují text úrovně 1 a odpovídající obdélníky obsahují text úrovně 2. Dobře funguje pro podrobné informace a minimální text úrovně 1. |
| StackedVenn | `106` | Používá se k zobrazení překrývajících se vztahů. Dobrá volba pro zdůraznění růstu nebo stupňování. Nejlépe funguje pouze s textem úrovně 1. Prvních sedm řádků textu úrovně 1 odpovídá kruhovému tvaru. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozvržení. |
| StaggeredProcess | `107` | Používá se k zobrazení sestupného postupu přes fáze. Každý z prvních pěti řádků textu úrovně 1 odpovídá obdélníku. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozvržení. |
| StepDownProcess | `108` | Používá se k zobrazení sestupného procesu s více kroky a podkroky. Nejlépe funguje s malým množstvím textu. |
| StepUpProcess | `109` | Používá se k zobrazení vzestupné řady kroků nebo seznamů informací. |
| SubStepProcess | `110` | Používá se k zobrazení víceúrovňového procesu s podkroky mezi každým výskytem textu úrovně 1. Nejlépe funguje s malým množstvím textu a je omezen na sedm kroků úrovně 1. Každý krok úrovně 1 může mít neomezený počet podkroků. |
| TableHierarchy | `111` | Používá se k zobrazení skupin informací vytvořených shora dolů a hierarchií v každé skupině. Toto rozvržení neobsahuje propojující čáry. |
| TableList | `112` | Používá se k zobrazení seskupených nebo souvisejících informací stejné hodnoty. První řádek textu úrovně 1 odpovídá hornímu tvaru a jeho text úrovně 2 se používá pro následující seznamy. |
| TargetList | `113` | Používá se k zobrazení provázaných nebo překrývajících se informací. Každý z prvních sedmi řádků textu úrovně 1 se objeví v obdélníkovém tvaru. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozvržení. Dobře funguje s textem úrovně 1 i úrovně 2. |
| TextCycle | `114` | Používá se k reprezentaci kontinuální posloupnosti fází, úkolů nebo událostí v kruhovém toku. Zdůrazňuje šipky nebo tok spíše než fáze nebo kroky. Nejlépe funguje pouze s textem úrovně 1. |
| TitlePictureLineup | `115` | Používá se k zobrazení řady obrázků, z nichž každý má vlastní titul a popis. Text úrovně 1 se zobrazí v rámečku nad obrázkem. Text úrovně 2 se zobrazí pod obrázkem. |
| TitledMatrix | `116` | Používá se k zobrazení vztahů čtyř kvadrantů k celku. První řádek textu úrovně 1 odpovídá centrálnímu tvaru a první čtyři řádky textu úrovně 2 se zobrazí v kvadrantech. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozvržení. |
| TitledPictureAccentList | `117` | Používá se k zobrazení seznamů informací s akcentním obrázkem ke každému textu úrovně 2. Text úrovně 1 se zobrazuje v samostatném rámečku v horní části seznamu. |
| TitledPictureBlocks | `118` | Používá se k zobrazení řady obrázků. Text úrovně 1 se zobrazuje nad každým obrázkem. Text úrovně 2 se zobrazuje po straně a mírně přes obrázek. |
| TrapezoidList | `119` | Používá se k zobrazení seskupených nebo souvisejících informací stejné hodnoty. Dobře funguje s velkým množstvím textu. |
| UpwardArrow | `120` | Používá se k zobrazení postupu nebo kroků směřujících vzhůru v úkolu, procesu nebo pracovním postupu. Každý z prvních pěti řádků textu úrovně 1 odpovídá bodu na šipce. Nejlépe funguje s minimálním textem. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozvržení. |
| VerticalAccentList | `121` | Používá se k zobrazení seznamů informací. Text úrovně 2 se zobrazuje v obdélníkových tvarech nad svislými špičatými tvary. Zdůrazňuje text úrovně 2 před textem úrovně 1 a je vhodný pro střední množství textu úrovně 2. |
| VerticalArrowList | `122` | Používá se k zobrazení postupu nebo sekvenčních kroků v úkolu, procesu nebo pracovním postupu směřujících k společnému cíli. Dobře funguje pro odrážkové seznamy informací. |
| VerticalBendingProcess | `123` | Používá se k zobrazení postupu nebo sekvenčních kroků v úkolu, procesu nebo pracovním postupu. Maximalizuje vodorovný i svislý prostor pro tvary. Klade větší důraz na vzájemné vztahy mezi tvary než na směr nebo pohyb. |
| VerticalBlockList | `124` | Používá se k zobrazení skupin informací nebo kroků v úkolu, procesu nebo pracovním postupu. Dobře funguje s velkým množstvím textu úrovně 2. Vhodné pro text s hlavním bodem a více podbody. |
| VerticalBoxList | `125` | Používá se k zobrazení několika skupin informací, zejména skupin s velkým množstvím textu úrovně 2. Vhodné pro odrážkové seznamy informací. |
| VerticalBulletList | `126` | Používá se k zobrazení netradičních nebo seskupených bloků informací. Dobře funguje pro seznamy s dlouhými nadpisy nebo informacemi na vyšší úrovni. |
| VerticalChevronList | `127` | Používá se k zobrazení postupu nebo sekvenčních kroků v úkolu, procesu nebo pracovním postupu, nebo k zdůraznění pohybu či směru. Zdůrazňuje text úrovně 2 před textem úrovně 1 a je vhodný pro velké množství textu úrovně 2. |
| VerticalCircleList | `128` | Používá se k zobrazení sekvenčních nebo seskupených dat. Nejlépe funguje pro text úrovně 1, který se zobrazí vedle velkého kruhového tvaru. Nižší úrovně textu jsou odděleny menšími kruhovými tvary. |
| VerticalCurvedList | `129` | Používá se k zobrazení zakřiveného seznamu informací. Pro přidání obrázků do akcentovaných kruhových tvarů použijte výplň obrázkem. |
| VerticalEquation | `130` | Používá se k zobrazení sekvenčních kroků nebo úkolů představujících plán či výsledek. Poslední řádek textu úrovně 1 se zobrazí za šipkou. Nejlépe funguje pouze s textem úrovně 1. |
| VerticalPictureAccentList | `131` | Používá se k zobrazení netradičních nebo seskupených bloků informací. Malé kruhy jsou určeny k umístění obrázků. |
| VerticalPictureList | `132` | Používá se k zobrazení netradičních nebo seskupených bloků informací. Malé tvary vlevo jsou určeny k umístění obrázků. |
| VerticalProcess | `133` | Používá se k zobrazení postupu nebo sekvenčních kroků v úkolu, procesu nebo pracovním postupu shora dolů. Nejlépe funguje s textem úrovně 1, protože svislý prostor je omezený. |
| Custom | `134` | Reprezentuje diagram SmartArt s vlastním šablonou rozvržení |
| PictureOrganizationChart | `135` | Používá se k zobrazení hierarchických informací nebo vztahů podřízenosti v organizaci, s odpovídajícími obrázky. Pomocný tvar a visící rozvržení organigramu jsou k dispozici s tímto rozvržením. |

### Viz také

* jmenný prostor [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->