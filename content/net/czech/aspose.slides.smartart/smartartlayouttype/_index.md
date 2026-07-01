---
title: SmartArtLayoutType
second_title: Aspose.Sildes pro .NET API Reference
description: Představuje typ rozložení SmartArt diagramu.
type: docs
weight: 10600
url: /cs/aspose.slides.smartart/smartartlayouttype/
---
## SmartArtLayoutType enumerace

Represents layout type of a SmartArt diagram.

```csharp
public enum SmartArtLayoutType
```

### Values

| Název | Hodnota | Popis |
| --- | --- | --- |
| AccentProcess | `0` | Použít pro zobrazení postupu, časové osy nebo sekvenčních kroků v úkolu, procesu nebo pracovním postupu. Dobře funguje pro znázornění textu úrovně 1 i úrovně 2. |
| AccentedPicture | `1` | Použít k zobrazení centrálního fotografického nápadu s přidruženými nápady po stranách. Horní text úrovně 1 se zobrazuje nad centrálním obrázkem. Odpovídající text pro další tvary úrovně 1 se zobrazuje vedle malých kruhových obrázků. Toto rozložení také dobře funguje bez textu. |
| AlternatingFlow | `2` | Použít k zobrazení skupin informací nebo sekvenčních kroků v úkolu, procesu nebo pracovním postupu. Zvýrazňuje interakci nebo vztahy mezi skupinami informací. |
| AlternatingHexagons | `3` | Použít k reprezentaci série propojených nápadů. Text úrovně 1 se objevuje uvnitř šestiúhelníků. Text úrovně 2 se objevuje mimo tvary. |
| AlternatingPictureBlocks | `4` | Použít k zobrazení série obrázků shora dolů. Text se střídavě objevuje vpravo nebo vlevo od obrázku. |
| AlternatingPictureCircles | `5` | Použít k zobrazení sady obrázků s textem. Odpovídající text se objevuje ve středových kruzích s obrázky střídavě zleva doprava. |
| ArrowRibbon | `6` | Použít k zobrazení souvisejících nebo kontrastních konceptů se spojením, jako jsou protichůdné síly. První dvě řádky textu úrovně 1 jsou použity jako text v šipkách. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozložení. |
| AscendingPictureAccentProcess | `7` | Použít k zobrazení vzestupné série obrázků s popisným textem. Funguje nejlépe s malým množstvím textu. |
| Balance | `8` | Použít k porovnání nebo zobrazení vztahu mezi dvěma nápady. Každý z prvních dvou řádků textu úrovně 1 odpovídá textu v horní části jedné strany středu. Zvýrazňuje text úrovně 2, který je omezen na čtyři tvary na každé straně středu. Rovnováha se nakloní ke straně s nejvíce tvary obsahujícími text úrovně 2. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozložení. |
| BasicBendingProcess | `9` | Použít k zobrazení postupu nebo sekvenčních kroků v úkolu, procesu nebo pracovním postupu. Maximalizuje vodorovný i svislý prostor pro tvary. |
| BasicBlockList | `10` | Použít k zobrazení nesekvenčních nebo seskupených bloků informací. Maximalizuje vodorovný i svislý prostor pro tvary. |
| BasicChevronProcess | `11` | Použít k zobrazení postupu; časové osy; sekvenčních kroků v úkolu, procesu nebo pracovním postupu; nebo pro zdůraznění pohybu či směru. Text úrovně 1 se objevuje uvnitř šipkového tvaru, zatímco text úrovně 2 se objevuje pod šipkovými tvary. |
| BasicCycle | `12` | Použít k reprezentaci pokračující sekvence fází, úkolů nebo událostí v kruhovém toku. Zvýrazňuje fáze nebo kroky spíše než spojující šipky nebo tok. Funguje nejlépe pouze s textem úrovně 1. |
| BasicMatrix | `13` | Použít k zobrazení vztahu komponent k celku ve čtvrtích. První čtyři řádky textu úrovně 1 se objevují v čtvrtích. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozložení. |
| BasicPie | `14` | Použít k zobrazení, jak jednotlivé části tvoří celek. Prvních sedm řádků textu úrovně 1 odpovídá rovnoměrně rozděleným výsečím nebo koláčovým tvarem. Horní tvar textu úrovně 1 se objevuje mimo zbytek koláče pro zdůraznění. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozložení. |
| BasicProcess | `15` | Použít k zobrazení postupu nebo sekvenčních kroků v úkolu, procesu nebo pracovním postupu. |
| BasicPyramid | `16` | Použít k zobrazení proporčních, propojených nebo hierarchických vztahů s největší komponentou dole a zužováním nahoru. Text úrovně 1 se objevuje v segmentech pyramidy a text úrovně 2 se objevuje ve tvarech podél každého segmentu. |
| BasicRadial | `17` | Použít k zobrazení vztahu k centrálnímu nápadu v cyklu. První řádek textu úrovně 1 odpovídá centrálnímu tvaru a jeho text úrovně 2 odpovídá okolním kruhovým tvarům. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozložení. |
| BasicTarget | `18` | Použít k zobrazení obsahu, stupňování nebo hierarchických vztahů. Prvních pět řádků textu úrovně 1 je spojeno s kruhem. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozložení. |
| BasicTimeline | `19` | Použít k zobrazení sekvenčních kroků v úkolu, procesu nebo pracovním postupu, nebo k zobrazení informací časové osy. Dobře funguje s textem úrovně 1 i úrovně 2. |
| BasicVenn | `20` | Použít k zobrazení překrývajících se nebo propojených vztahů. Prvních sedm řádků textu úrovně 1 odpovídá kruhu. Pokud je čtyři nebo méně řádků textu úrovně 1, text je uvnitř kruhů. Pokud je více než čtyři řádky, text je mimo kruhy. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozložení. |
| BendingPictureAccentList | `21` | Použít k zobrazení nesekvenčních nebo seskupených bloků informací. Malé kruhové tvary jsou určeny pro obrázky. Dobře funguje pro znázornění textu úrovně 1 i úrovně 2. Maximalizuje vodorovný i svislý prostor pro tvary. |
| BendingPictureBlocks | `22` | Použít k zobrazení série obrázků. Box v dolním rohu může obsahovat malé množství textu. |
| BendingPictureCaption | `23` | Použít k zobrazení sekvenční série obrázků. Box v dolním rohu může obsahovat malé množství textu. |
| BendingPictureCaptionList | `24` | Použít k zobrazení série obrázků. Název a popis se objevují v popiskovém tvaru pod každým obrázkem. |
| BendingPictureSemiTransparentText | `25` | Použít k zobrazení série obrázků. Poloprůhledný box zakrývá spodní část obrázku a obsahuje všechny úrovně textu. |
| BlockCycle | `26` | Použít k reprezentaci pokračující sekvence fází, úkolů nebo událostí v kruhovém toku. Zvýrazňuje fáze nebo kroky spíše než spojující šipky nebo tok. |
| BubblePictureList | `27` | Použít k zobrazení série obrázků. Může obsahovat až osm obrázků úrovně 1. Nepoužitý text a obrázky se nezobrazí, ale zůstávají k dispozici při změně rozložení. Funguje nejlépe s malým množstvím textu. |
| CaptionedPictures | `28` | Použít k zobrazení obrázků s více úrovněmi textu. Funguje nejlépe s malým množstvím textu úrovně 1 a středním množstvím textu úrovně 2. |
| ChevronList | `29` | Použít k zobrazení postupu skrze několik procesů, které tvoří celkový pracovní postup. Také funguje pro znázornění kontrastních procesů. Text úrovně 1 odpovídá prvnímu šipkovému tvaru vlevo, zatímco text úrovně 2 odpovídá horizontálním pods krokům pro každý tvar, který obsahuje text úrovně 1. |
| CircleAccentTimeline | `30` | Použít k zobrazení série událostí nebo informací časové osy. Text úrovně 1 se objevuje vedle větších kruhových tvarů. Text úrovně 2 se objevuje vedle menších kruhových tvarů. |
| CircleArrowProcess | `31` | Použít k zobrazení sekvenčních položek s podpůrným textem pro každou položku. Tento diagram funguje nejlépe s malým množstvím textu úrovně 1. |
| CirclePictureHierarchy | `32` | Použít k zobrazení hierarchických informací nebo vztahů podřizení v organizaci. Obrázky se objevují v kruzích a odpovídající text se zobrazuje vedle obrázků. |
| CircleRelationship | `33` | Použít k zobrazení vztahu k nebo od centrálního nápadu. Text úrovně 2 je přidán nesekvenčně a je omezen na pět položek. Může existovat jen jedna položka úrovně 1. |
| CircularBendingProcess | `34` | Použít k zobrazení dlouhé nebo nelineární sekvence nebo kroků v úkolu, procesu nebo pracovním postupu. Funguje nejlépe pouze s textem úrovně 1. Maximalizuje vodorovný i svislý prostor pro tvary. |
| CircularPictureCallout | `35` | Použít k zobrazení centrálního nápadu a podnápadů nebo souvisejících položek. Text pro první obrázek zakrývá spodní část obrázku. Odpovídající text pro další tvary úrovně 1 se zobrazuje vedle malých kruhových obrázků. Tento diagram také dobře funguje bez textu. |
| ClosedChevronProcess | `36` | Použít k zobrazení postupu, časové osy nebo sekvenčních kroků v úkolu, procesu nebo pracovním postupu, nebo pro zdůraznění pohybu či směru. Může být použit k zdůraznění informací v počátečním tvaru. Funguje nejlépe pouze s textem úrovně 1. |
| ContinuousArrowProcess | `37` | Použít k zobrazení časové osy nebo sekvenčních kroků v úkolu, procesu nebo pracovním postupu. Funguje nejlépe s textem úrovně 1, protože každý řádek textu úrovně 1 se objevuje uvnitř šipkového tvaru. Text úrovně 2 se objevuje mimo šipkový tvar. |
| ContinuousBlockProcess | `38` | Použít k zobrazení postupu nebo sekvenčních kroků v úkolu, procesu nebo pracovním postupu. Funguje nejlépe s minimálním textem úrovně 1 i úrovně 2. |
| ContinuousCycle | `39` | Použít k reprezentaci pokračující sekvence fází, úkolů nebo událostí v kruhovém toku. Zvýrazňuje spojení mezi všemi komponentami. Funguje nejlépe pouze s textem úrovně 1. |
| ContinuousPictureList | `40` | Použít k zobrazení skupin propojených informací. Kruhové tvary jsou navrženy pro obrázky. |
| ConvergingArrows | `41` | Použít k zobrazení nápadů nebo konceptů, které se sbíhají do centrálního bodu. Funguje nejlépe pouze s textem úrovně 1. |
| ConvergingRadial | `42` | Použít k zobrazení vztahů konceptů nebo komponent k centrálnímu nápadu v cyklu. První řádek textu úrovně 1 odpovídá centrálnímu kruhovému tvaru a řádky textu úrovně 2 odpovídají okolním obdélníkovým tvarům. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozložení. |
| CounterbalanceArrows | `43` | Použít k zobrazení dvou protichůdných nápadů nebo konceptů. Každý z prvních dvou řádků textu úrovně 1 odpovídá šipce a dobře funguje s textem úrovně 2. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozložení. |
| CycleMatrix | `44` | Použít k zobrazení vztahu k centrálnímu nápadu v cyklickém postupu. Každý ze čtyř prvních řádků textu úrovně 1 odpovídá výsečovému nebo koláčovému tvaru a text úrovně 2 se objevuje v obdélníkovém tvaru po straně výseče nebo koláčového tvaru. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozložení. |
| DescendingBlockList | `45` | Použít k zobrazení skupin souvisejících nápadů nebo seznamů informací. Textové tvary klesají výškově sekvenčně a text úrovně 1 se zobrazuje svisle. |
| DescendingProcess | `46` | Použít k zobrazení klesající série událostí. První text úrovně 1 je v horní části šipky a poslední text úrovně 1 se zobrazuje ve spodní části šipky. Zobrazuje se jen prvních sedm položek úrovně 1. Funguje nejlépe s malým až středním množstvím textu. |
| DetailedProcess | `47` | Použít s velkým množstvím textu úrovně 2 k zobrazení postupu přes fáze. |
| DivergingArrows | `48` | Použít k zobrazení nápadů nebo konceptů, které se rozšiřují od centrálního zdroje. Funguje nejlépe pouze s textem úrovně 1. |
| DivergingRadial | `49` | Použít k zobrazení vztahů k centrálnímu nápadu v cyklu. První řádek textu úrovně 1 odpovídá centrálnímu kruhovému tvaru. Zvýrazňuje okolní kruhy spíše než centrální nápad. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozložení. |
| Equation | `50` | Použít k zobrazení sekvenčních kroků nebo úkolů, které znázorňují plán nebo výsledek. Poslední řádek textu úrovně 1 se objevuje za rovnítkem (=). Funguje nejlépe pouze s textem úrovně 1. |
| FramedTextPicture | `51` | Použít k zobrazení obrázků s odpovídajícím textem úrovně 1 zobrazeným v rámečku. |
| Funnel | `52` | Použít k zobrazení filtrování informací nebo toho, jak se části spojují do celku. Zvýrazňuje finální výsledek. Může obsahovat až čtyři řádky textu úrovně 1; poslední z těchto čtyř řádků se objevuje pod trychtýřem a ostatní řádky odpovídají kruhovému tvaru. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozložení. |
| Gear | `53` | Použít k zobrazení propojených nápadů. Každý ze tří prvních řádků textu úrovně 1 odpovídá tvaru ozubeného kola a jejich odpovídající text úrovně 2 se objevuje v obdélnících vedle tvaru kola. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozložení. |
| GridMatrix | `54` | Použít k zobrazení umístění konceptů podél dvou os. Zvýrazňuje jednotlivé komponenty spíše než celek. První čtyři řádky textu úrovně 1 se objevují ve čtvrtích. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozložení. |
| GroupedList | `55` | Použít k zobrazení skupin a podskupin informací, nebo kroků a podkroků v úkolu, procesu nebo pracovním postupu. Text úrovně 1 odpovídá vodorovným tvarům nejvyšší úrovně a text úrovně 2 odpovídá vertikálním podkrokům pod každým souvisejícím tvarem vyšší úrovně. Dobře funguje pro zdůraznění podskupin nebo podkroků, hierarchických informací nebo více seznamů informací. |
| HalfCircleOrganizationChart | `56` | Použít k zobrazení hierarchických informací nebo vztahů podřizení v organizaci. Asistentské tvary a rozložení visících organigramů jsou k dispozici s tímto rozložením. |
| HexagonCluster | `57` | Použít k zobrazení obrázků s přidruženým popisným textem. Malé šestiúhelníky označují pár obrázek-text. Funguje nejlépe s malým množstvím textu. |
| Hierarchy | `58` | Použít k zobrazení hierarchických vztahů postupujících shora dolů. |
| HierarchyList | `59` | Použít k zobrazení hierarchických vztahů postupujících přes skupiny. Může být také použito ke skupinování nebo výčtu informací. |
| HorizontalBulletList | `60` | Použít k zobrazení nesekvenčních nebo seskupených seznamů informací. Funguje dobře s velkým množstvím textu. Veškerý text má stejnou úroveň důrazu a směr není naznačen. |
| HorizontalHierarchy | `61` | Použít k zobrazení hierarchických vztahů postupujících vodorovně. Funguje dobře pro rozhodovací stromy. |
| HorizontalLabeledHierarchy | `62` | Použít k zobrazení hierarchických vztahů postupujících vodorovně a seskupených hierarchicky. Zvýrazňuje nadpis nebo text úrovně 1. První řádek textu úrovně 1 se objevuje v tvaru na začátku hierarchie a druhý a všechny následující řádky textu úrovně 1 se objevují v horní části vysokých obdélníků. |
| HorizontalMultiLevelHierarchy | `63` | Použít k zobrazení velkého množství hierarchických informací postupujících vodorovně. Vrchol hierarchie je zobrazen svisle. Toto rozložení podporuje mnoho úrovní v hierarchii. |
| HorizontalOrganizationChart | `64` | Použít k zobrazení hierarchických informací vodorovně nebo vztahů podřizení v organizaci. Asistentský tvar a rozložení visících organigramů jsou k dispozici s tímto rozložením. |
| HorizontalPictureList | `65` | Použít k zobrazení nesekvenčních nebo seskupených informací se zaměřením na související obrázky. Horní tvary jsou navrženy pro obrázky. |
| IncreasingArrowsProcess | `66` | Použít k zobrazení sekvenčních a překrývajících se kroků v procesu. Omezeno na pět položek úrovně 1. Úroveň 2 může obsahovat velké množství textu. |
| IncreasingCircleProcess | `67` | Použít k zobrazení série kroků, přičemž vnitřek kruhu se zvětšuje s každým krokem. Omezeno na sedm kroků úrovně 1, ale neomezený počet položek úrovně 2. Funguje dobře s velkým množstvím textu úrovně 2. |
| InvertedPyramid | `68` | Použít k zobrazení proporčních, propojených nebo hierarchických vztahů s největší komponentou nahoře a zúžením dolů. Text úrovně 1 se objevuje v segmentech pyramidy a text úrovně 2 se objevuje ve tvarech podél každého segmentu. |
| LabeledHierarchy | `69` | Použít k zobrazení hierarchických vztahů postupujících shora dolů a seskupených hierarchicky. Zvýrazňuje nadpis nebo text úrovně 1. První řádek textu úrovně 1 se objevuje v tvaru na začátku hierarchie a všechny následující řádky textu úrovně 1 se objevují vlevo od dlouhých obdélníků. |
| LinearVenn | `70` | Použít k zobrazení překrývajících se vztahů v sekvenci. Funguje nejlépe pouze s textem úrovně 1. |
| LinedList | `71` | Použít k zobrazení velkého množství textu rozděleného do kategorií a podkategorií. Funguje dobře s více úrovněmi textu. Text na stejné úrovni je oddělen čarami. |
| MultidirectionalCycle | `72` | Použít k reprezentaci pokračující sekvence fází, úkolů nebo událostí, které se mohou objevit libovolným směrem. |
| NameandTitleOrganizationChart | `73` | Použít k zobrazení hierarchických informací nebo vztahů podřizení v organizaci. Pro zadání textu do titulkového pole napište přímo do menšího obdélníkového tvaru. Asistentský tvar a rozložení visících organigramů jsou k dispozici s tímto rozložením. |
| NestedTarget | `74` | Použít k zobrazení vztahů obsahu. Každý ze tří prvních řádků textu úrovně 1 odpovídá levému hornímu textu ve tvarech a text úrovně 2 odpovídá menším tvarům. Funguje nejlépe s minimálním počtem řádků textu úrovně 2. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozložení. |
| NondirectionalCycle | `75` | Použít k reprezentaci pokračující sekvence fází, úkolů nebo událostí v kruhovém toku. Každý tvar má stejnou úroveň důležitosti. Funguje dobře, když není potřeba naznačit směr. |
| OpposingArrows | `76` | Použít k zobrazení dvou protichůdných nápadů nebo konceptů, které se rozcházejí z centrálního bodu. Každý z prvních dvou řádků textu úrovně 1 odpovídá šipce a dobře funguje s textem úrovně 2. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozložení. |
| OpposingIdeas | `77` | Použít k zobrazení dvou protichůdných nebo kontrastních nápadů. Může mít jednu nebo dvě položky úrovně 1. Každý text úrovně 1 může obsahovat více podúrovní. Funguje dobře s velkým množstvím textu. |
| OrganizationChart | `78` | Použít k zobrazení hierarchických informací nebo vztahů podřizení v organizaci. Asistentský tvar a rozložení visících organigramů jsou k dispozici s tímto rozložením. |
| PhasedProcess | `79` | Použít k zobrazení tří fází procesu. Omezeno na tři položky úrovně 1. První dvě položky úrovně 1 mohou každá obsahovat čtyři položky úrovně 2 a třetí položka úrovně 1 může obsahovat neomezený počet položek úrovně 2. Funguje nejlépe s malým množstvím textu. |
| PictureAccentBlocks | `80` | Použít k zobrazení skupiny obrázků v blocích od rohu. Odpovídající text se zobrazuje svisle. Dobře funguje jako akcent na titulních nebo podtitulních snímcích či jako oddělovač sekcí dokumentu. |
| PictureAccentList | `81` | Použít k zobrazení seskupených nebo souvisejících informací. Malé tvary v horních rozích jsou určeny k obrázkům. Zvýrazňuje text úrovně 2 nad textem úrovně 1 a je vhodná pro velké množství textu úrovně 2. |
| PictureAccentProcess | `82` | Použít k zobrazení sekvenčních kroků v úkolu, procesu nebo pracovním postupu. Obdélníkové tvary v pozadí jsou určeny pro obrázky. |
| PictureCaptionList | `83` | Použít k zobrazení nesekvenčních nebo seskupených bloků informací. Horní tvary jsou určeny pro obrázky a obrázky jsou upřednostňovány před textem. Funguje dobře pro obrázky s krátkými popisky. |
| PictureGrid | `84` | Použít k zobrazení obrázků uspořádaných do čtvercové mřížky. Nejlépe s malým množstvím textu úrovně 1, který se objevuje nad obrázkem. |
| PictureLineup | `85` | Použít k zobrazení série obrázků vedle sebe. Text úrovně 1 pokrývá horní část obrázku. Text úrovně 2 se objevuje pod obrázkem. |
| PictureStrips | `86` | Použít k zobrazení série obrázků shora dolů s textem úrovně 1 vedle každého. |
| PieProcess | `87` | Použít k zobrazení kroků v procesu, kde každá výseč koláče roste až na sedm tvarů. Text úrovně 1 se zobrazuje svisle. |
| PlusandMinus | `88` | Použít k zobrazení výhod a nevýhod dvou nápadů. Každý text úrovně 1 může obsahovat více podúrovní. Funguje dobře s velkým množstvím textu. Omezeno na dvě položky úrovně 1. |
| ProcessArrows | `89` | Použít k zobrazení informací ilustrujících proces nebo pracovní postup. Text úrovně 1 se objevuje v kruhových tvarech a text úrovně 2 se objevuje v šipkových tvarech. Funguje nejlépe s minimálním textem a pro zdůraznění pohybu nebo směru. |
| ProcessList | `90` | Použít k zobrazení několika skupin informací nebo kroků a podkroků v úkolu, procesu nebo pracovním postupu. Text úrovně 1 odpovídá horním vodorovným tvarům a text úrovně 2 odpovídá vertikálním podkrokům pod každým souvisejícím tvarem nejvyšší úrovně. |
| PyramidList | `91` | Použít k zobrazení proporčních, propojených nebo hierarchických vztahů. Text se objevuje v obdélníkových tvarech nad pyramidovým pozadím. |
| RadialCluster | `92` | Použít k zobrazení dat vztahujících se k centrálnímu nápadu nebo tématu. Horní text úrovně 1 se objevuje uprostřed. Text úrovně 2 se objevuje v okolních tvarech. Může obsahovat až sedm tvarů úrovně 2. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozložení. Funguje nejlépe s malým množstvím textu. |
| RadialCycle | `93` | Použít k zobrazení vztahu k centrálnímu nápadu. Zvýrazňuje jak informace ve středovém kruhu, tak to, jak informace vnějšího prstence kruhů přispívají k centrálnímu nápadu. První řádek textu úrovně 1 odpovídá středovému kruhu a jeho text úrovně 2 odpovídá vnějšímu prstenci kruhů. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozložení. |
| RadialList | `94` | Použít k zobrazení vztahů k centrálnímu nápadu v cyklu. Středový tvar může obsahovat obrázek. Text úrovně 1 se objevuje v menších kruzích a jakýkoli související text úrovně 2 se objevuje po straně menších kruhů. |
| RadialVenn | `95` | Použít k zobrazení jak překrývajících se vztahů, tak vztahu k centrálnímu nápadu v cyklu. První řádek textu úrovně 1 odpovídá centrálnímu tvaru a řádky textu úrovně 2 odpovídají okolním kruhovým tvarům. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozložení. |
| RandomToResultProcess | `96` | Použít k zobrazení, jak řadou kroků mohou chaotické nápady vést k jednotnému cíli nebo nápadu. Podporuje více položek textu úrovně 1, ale první a poslední odpovídající tvary úrovně 1 jsou pevně dané. Funguje nejlépe s malým množstvím textu úrovně 1 a středním množstvím textu úrovně 2. |
| RepeatingBendingProcess | `97` | Použít k zobrazení postupu nebo sekvenčních kroků v úkolu, procesu nebo pracovním postupu. Maximalizuje vodorovný i svislý prostor pro tvary. |
| ReverseList | `98` | Použít k změně mezi dvěma položkami. Zobrazuje se jen první dva položky textu a každá položka může obsahovat velké množství textu. Funguje dobře pro zobrazení změny mezi dvěma položkami nebo posunu v pořadí. |
| SegmentedCycle | `99` | Použít k zobrazení postupu nebo sekvence fází, úkolů nebo událostí v kruhovém toku. Zvýrazňuje propojené části. Každý ze sedmi prvních řádků textu úrovně 1 odpovídá výsečovému nebo koláčovému tvaru. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozložení. |
| SegmentedProcess | `100` | Použít k zobrazení postupu nebo sekvenčních kroků v úkolu, procesu nebo pracovním postupu. Zvýrazňuje text úrovně 2, protože každý řádek se objevuje v samostatném tvaru. |
| SegmentedPyramid | `101` | Použít k zobrazení vztahů obsahu, proporčních nebo propojených. Prvních devět řádků textu úrovně 1 se objevuje v trojúhelníkových tvarech. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozložení. Funguje nejlépe pouze s textem úrovně 1. |
| SnapshotPictureList | `102` | Použít k zobrazení obrázků s vysvětlujícím textem. Text úrovně 2 může zobrazovat seznamy informací. Funguje dobře s velkým množstvím textu. |
| SpiralPicture | `103` | Použít k zobrazení série až pěti obrázků s odpovídajícími popisky úrovně 1, které spirálově směřují do středu. |
| SquareAccentList | `104` | Použít k zobrazení seznamů informací rozdělených do kategorií. Text úrovně 2 se objevuje vedle malého čtvercového tvaru. Funguje dobře s velkým množstvím textu úrovně 2. |
| StackedList | `105` | Použít k zobrazení skupin informací nebo kroků v úkolu, procesu nebo pracovním postupu. Kruhové tvary obsahují text úrovně 1 a odpovídající obdélníky obsahují text úrovně 2. Funguje dobře pro mnoho detailů a minimální text úrovně 1. |
| StackedVenn | `106` | Použít k zobrazení překrývajících se vztahů. Dobrá volba pro zdůraznění růstu nebo stupňování. Funguje nejlépe pouze s textem úrovně 1. Prvních sedm řádků textu úrovně 1 odpovídá kruhovému tvaru. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozložení. |
| StaggeredProcess | `107` | Použít k zobrazení sestupného postupu přes fáze. Každý z pěti prvních řádků textu úrovně 1 odpovídá obdélníku. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozložení. |
| StepDownProcess | `108` | Použít k zobrazení klesajícího procesu s více kroky a podkroky. Funguje nejlépe s malým množstvím textu. |
| StepUpProcess | `109` | Použít k zobrazení vzestupné série kroků nebo seznamů informací. |
| SubStepProcess | `110` | Použít k zobrazení procesů s více kroky a podkroky mezi každou položkou textu úrovně 1. Funguje nejlépe s malým množstvím textu a je omezeno na sedm kroků úrovně 1. Každý krok úrovně 1 může mít neomezený počet podkroků. |
| TableHierarchy | `111` | Použít k zobrazení skupin informací postavených shora dolů a hierarchií v každé skupině. Toto rozložení neobsahuje spojující čáry. |
| TableList | `112` | Použít k zobrazení seskupených nebo souvisejících informací stejné hodnoty. První řádek textu úrovně 1 odpovídá hornímu tvaru a jeho text úrovně 2 se používá pro následné seznamy. |
| TargetList | `113` | Použít k zobrazení vzájemně souvisejících nebo překrývajících se informací. Každý z prvních sedmi řádků textu úrovně 1 se objevuje v obdélníkovém tvaru. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozložení. Funguje dobře s textem úrovně 1 i úrovně 2. |
| TextCycle | `114` | Použít k reprezentaci pokračující sekvence fází, úkolů nebo událostí v kruhovém toku. Zvýrazňuje šipky nebo tok spíše než fáze nebo kroky. Funguje nejlépe pouze s textem úrovně 1. |
| TitlePictureLineup | `115` | Použít k zobrazení série obrázků, z nichž každý má vlastní titulek a popis. Text úrovně 1 se objevuje v boxu nad obrázkem. Text úrovně 2 se objevuje pod obrázkem. |
| TitledMatrix | `116` | Použít k zobrazení vztahů čtyř čtvrtí k celku. První řádek textu úrovně 1 odpovídá centrálnímu tvaru a první čtyři řádky textu úrovně 2 se objevují v čtvrtích. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozložení. |
| TitledPictureAccentList | `117` | Použít k zobrazení seznamů informací s akcentním obrázkem pro každý text úrovně 2. Text úrovně 1 se zobrazuje v samostatném boxu nahoře nad seznamem. |
| TitledPictureBlocks | `118` | Použít k zobrazení série obrázků. Text úrovně 1 se objevuje nad každým obrázkem. Text úrovně 2 se objevuje po straně a mírně překrývá každý obrázek. |
| TrapezoidList | `119` | Použít k zobrazení seskupených nebo souvisejících informací stejné hodnoty. Funguje dobře s velkým množstvím textu. |
| UpwardArrow | `120` | Použít k zobrazení postupu nebo kroků, které směřují vzhůru v úkolu, procesu nebo pracovním postupu. Každý z pěti prvních řádků textu úrovně 1 odpovídá bodu na šipce. Funguje nejlépe s minimálním textem. Nepoužitý text se nezobrazuje, ale zůstává k dispozici při změně rozložení. |
| VerticalAccentList | `121` | Použít k zobrazení seznamů informací. Text úrovně 2 se objevuje v obdélníkových tvarech nad svislými šipkami. Zvýrazňuje text úrovně 2 nad textem úrovně 1 a je vhodná pro střední množství textu úrovně 2. |
| VerticalArrowList | `122` | Použít k zobrazení postupu nebo sekvenčních kroků v úkolu, procesu nebo pracovním postupu, které směřují k společnému cíli. Funguje dobře pro odrážkové seznamy informací. |
| VerticalBendingProcess | `123` | Použít k zobrazení postupu nebo sekvenčních kroků v úkolu, procesu nebo pracovním postupu. Maximalizuje vodorovný i svislý prostor pro tvary. Dává větší důraz na vzájemné vztahy mezi tvary než na směr nebo pohyb. |
| VerticalBlockList | `124` | Použít k zobrazení skupin informací nebo kroků v úkolu, procesu nebo pracovním postupu. Funguje dobře s velkým množstvím textu úrovně 2. Dobrá volba pro text s hlavním bodem a mnoha podbody. |
| VerticalBoxList | `125` | Použít k zobrazení několika skupin informací, zejména skupin s velkým množstvím textu úrovně 2. Dobrá volba pro odrážkové seznamy informací. |
| VerticalBulletList | `126` | Použít k zobrazení nesekvenčních nebo seskupených bloků informací. Funguje dobře pro seznamy s dlouhými nadpisy nebo informacemi nejvyšší úrovně. |
| VerticalChevronList | `127` | Použít k zobrazení postupu nebo sekvenčních kroků v úkolu, procesu nebo pracovním postupu, či pro zdůraznění pohybu či směru. Zvýrazňuje text úrovně 2 nad textem úrovně 1 a je vhodná pro velké množství textu úrovně 2. |
| VerticalCircleList | `128` | Použít k zobrazení sekvenčních nebo seskupených dat. Funguje nejlépe pro text úrovně 1, který se zobrazuje vedle velkého kruhového tvaru. Nižší úrovně textu jsou odděleny menšími kruhovými tvary. |
| VerticalCurvedList | `129` | Použít k zobrazení zakřiveného seznamu informací. Pro přidání obrázků do akcentních kruhových tvarů použijte výplň obrázkem. |
| VerticalEquation | `130` | Použít k zobrazení sekvenčních kroků nebo úkolů, které znázorňují plán nebo výsledek. Poslední řádek textu úrovně 1 se objevuje za šipkou. Funguje nejlépe pouze s textem úrovně 1. |
| VerticalPictureAccentList | `131` | Použít k zobrazení nesekvenčních nebo seskupených bloků informací. Malé kruhy jsou určeny pro obrázky. |
| VerticalPictureList | `132` | Použít k zobrazení nesekvenčních nebo seskupených bloků informací. Malé tvary vlevo jsou určeny pro obrázky. |
| VerticalProcess | `133` | Použít k zobrazení postupu nebo sekvenčních kroků v úkolu, procesu nebo pracovním postupu shora dolů. Funguje nejlépe s textem úrovně 1, protože svislý prostor je omezený. |
| Custom | `134` | Represents a SmartArt diagram with custom layout template |
| PictureOrganizationChart | `135` | Use to show hierarchical information or reporting relationships in an organization, with corresponding pictures. The assistant shape and Org Chart hanging layouts are available with this layout. |

### See Also

* namespace [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->