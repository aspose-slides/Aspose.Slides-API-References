---
title: SmartArtLayoutType
second_title: Aspose.Slides för C++ API-referens
description: Representerar layouttyp för ett SmartArt-diagram.
type: docs
weight: 157
url: /sv/aspose.slides.smartart/smartartlayouttype/
---
## SmartArtLayoutType enum


Representerar layouttyp för ett [SmartArt](../smartart/) diagram.

```cpp
enum class SmartArtLayoutType
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| AccentProcess | 0 | Används för att visa en progression, en tidslinje eller sekventiella steg i en uppgift, process eller arbetsflöde. Fungerar bra för att illustrera både Nivå 1- och Nivå 2-text. |
| AccentedPicture | 1 | Används för att visa en central, fotografisk idé med relaterade idéer på sidan. Den översta Nivå 1-texten visas över den centrala bilden. Tillhörande text för andra Nivå 1-former visas bredvid de små cirkulära bilderna. Denna layout fungerar också bra utan text. |
| AlternatingFlow | 2 | Används för att visa grupper av information eller sekventiella steg i en uppgift, process eller arbetsflöde. Betonar interaktionen eller relationerna mellan informationsgrupperna. |
| AlternatingHexagons | 3 | Används för att representera en serie sammankopplade idéer. Nivå 1-text visas i hexagonerna. Nivå 2-text visas utanför formerna. |
| AlternatingPictureBlocks | 4 | Används för att visa en serie bilder från topp till botten. Text visas växelvis till höger eller vänster om bilden. |
| AlternatingPictureCircles | 5 | Används för att visa en uppsättning bilder med text. Den motsvarande texten visas i de centrala cirklarna med bilderna växlande från vänster till höger. |
| ArrowRibbon | 6 | Används för att visa antingen relaterade eller kontrasterande begrepp med någon koppling, såsom motsatta krafter. De två första raderna av Nivå 1-text används för text i pilarna. Oanvänd text visas inte, men förblir tillgänglig om du byter layout. |
| AscendingPictureAccentProcess | 7 | Används för att visa en stigande serie bilder med beskrivande text. Fungerar bäst med en liten mängd text. |
| Balance | 8 | Används för att jämföra eller visa förhållandet mellan två idéer. Varje av de två första raderna av Nivå 1-text motsvarar text högst upp på ena sidan av mittpunkten. Betonar Nivå 2-text, som är begränsad till fyra former på varje sida av mittpunkten. Balanseringen lutar mot den sida med flest former som innehåller Nivå 2-text. Oanvänd text visas inte, men förblir tillgänglig om du byter layout. |
| BasicBendingProcess | 9 | Används för att visa en progression eller sekventiella steg i en uppgift, process eller arbetsflöde. Maximiserar både horisontellt och vertikalt utrymme för former. |
| BasicBlockList | 10 | Används för att visa icke-sekventiella eller grupperade informationsblock. Maximiserar både horisontellt och vertikalt utrymme för former. |
| BasicChevronProcess | 11 | Används för att visa en progression; en tidslinje; sekventiella steg i en uppgift, process eller arbetsflöde; eller för att betona rörelse eller riktning. Nivå 1-text visas i en pilform medan Nivå 2-text visas under pilarna. |
| BasicCycle | 12 | Används för att representera en fortsättande sekvens av faser, uppgifter eller händelser i ett cirkulärt flöde. Betonar faserna eller stegen snarare än de anslutande pilarna eller flödet. Fungerar bäst endast med Nivå 1-text. |
| BasicMatrix | 13 | Används för att visa relationen mellan komponenter och en helhet i kvadranter. De fyra första raderna av Nivå 1-text visas i kvadranterna. Oanvänd text visas inte, men förblir tillgänglig om du byter layout. |
| BasicPie | 14 | Används för att visa hur enskilda delar bildar en helhet. De sju första raderna av Nivå 1-text motsvarar de jämnt fördelade segmenten eller pajformerna. Den övre Nivå 1-textformen visas utanför resten av pajen för betoning. Oanvänd text visas inte, men förblir tillgänglig om du byter layout. |
| BasicProcess | 15 | Används för att visa en progression eller sekventiella steg i en uppgift, process eller arbetsflöde. |
| BasicPyramid | 16 | Används för att visa proportionella, sammankopplade eller hierarkiska relationer med den största komponenten längst ner och smalnande uppåt. Nivå 1-text visas i pyramidesegmenten och Nivå 2-text visas i former bredvid varje segment. |
| BasicRadial | 17 | Används för att visa relationen till en central idé i en cykel. Den första raden av Nivå 1-text motsvarar den centrala formen, och dess Nivå 2-text motsvarar de omgivande cirkulära formerna. Oanvänd text visas inte, men förblir tillgänglig om du byter layout. |
| BasicTarget | 18 | Används för att visa inneslutning, graderingar eller hierarkiska relationer. De fem första raderna av Nivå 1-text är kopplade till en cirkel. Oanvänd text visas inte, men förblir tillgänglig om du byter layout. |
| BasicTimeline | 19 | Används för att visa sekventiella steg i en uppgift, process eller arbetsflöde, eller för att visa tidslinjeinformation. Fungerar bra med både Nivå 1- och Nivå 2-text. |
| BasicVenn | 20 | Används för att visa överlappande eller sammankopplade relationer. De sju första raderna av Nivå 1-text motsvarar en cirkel. Om det finns fyra eller färre rader av Nivå 1-text är texten inne i cirklarna. Om det finns fler än fyra rader av Nivå 1-text är texten utanför cirklarna. Oanvänd text visas inte, men förblir tillgänglig om du byter layout. |
| BendingPictureAccentList | 21 | Används för att visa icke-sekventiella eller grupperade informationsblock. De små cirkulära formerna är avsedda att innehålla bilder. Fungerar bra för att illustrera både Nivå 1- och Nivå 2-text. Maximiserar både horisontellt och vertikalt utrymme för former. |
| BendingPictureBlocks | 22 | Används för att visa en serie bilder. Boxen som täcker det nedre hörnet kan innehålla små mängder text. |
| BendingPictureCaption | 23 | Används för att visa en sekventiell serie bilder. Boxen som täcker det nedre hörnet kan innehålla små mängder text. |
| BendingPictureCaptionList | 24 | Används för att visa en serie bilder. Titel och beskrivning visas i en pratbubbelform under varje bild. |
| BendingPictureSemiTransparentText | 25 | Används för att visa en serie bilder. En semitransparent box täcker den nedre delen av bilden och innehåller alla nivåer av text. |
| BlockCycle | 26 | Används för att representera en fortsättande sekvens av faser, uppgifter eller händelser i ett cirkulärt flöde. Betonar faserna eller stegen snarare än de anslutande pilarna eller flödet. |
| BubblePictureList | 27 | Används för att visa en serie bilder. Kan innehålla upp till åtta Nivå 1-bilder. Oanvänd text och bilder visas inte, men förblir tillgängliga om du byter layout. Fungerar bäst med små mängder text. |
| CaptionedPictures | 28 | Används för att visa bilder med flera nivåer av text. Fungerar bäst med en liten mängd Nivå 1-text och en medelstor mängd Nivå 2-text. |
| ChevronList | 29 | Används för att visa en progression genom flera processer som utgör ett övergripande arbetsflöde. Fungerar också för att illustrera kontrasterande processer. Nivå 1-text motsvarar den första pilformen till vänster, medan Nivå 2-text motsvarar horisontella delsteg för varje form som innehåller Nivå 1-text. |
| CircleAccentTimeline | 30 | Används för att visa en serie händelser eller tidslinjeinformation. Nivå 1-text visas bredvid större cirkulära former. Nivå 2-text visas bredvid mindre cirkulära former. |
| CircleArrowProcess | 31 | Används för att visa sekventiella objekt med stödjande text för varje objekt. Detta diagram fungerar bäst med små mängder Nivå 1-text. |
| CirclePictureHierarchy | 32 | Används för att visa hierarkisk information eller rapporteringsrelationer i en organisation. Bilder visas i cirklar och motsvarande text visas bredvid bilderna. |
| CircleRelationship | 33 | Används för att visa relationen till eller från en central idé. Nivå 2-text läggs till icke-sekventiellt och är begränsad till fem objekt. Det kan bara finnas ett Nivå 1-objekt. |
| CircularBendingProcess | 34 | Används för att visa en lång eller nonlinear sekvens eller steg i en uppgift, process eller arbetsflöde. Fungerar bäst endast med Nivå 1-text. Maximiserar både horisontellt och vertikalt utrymme för former. |
| CircularPictureCallout | 35 | Används för att visa en central idé och underidéer eller relaterade objekt. Texten för den första bilden täcker bildens nedre del. Motsvarande text för andra Nivå 1-former visas bredvid de små cirkulära bilderna. Detta diagram fungerar också bra utan text. |
| ClosedChevronProcess | 36 | Används för att visa en progression, en tidslinje eller sekventiella steg i en uppgift, process eller arbetsflöde, eller för att betona rörelse eller riktning. Kan användas för att betona information i startformen. Fungerar bäst endast med Nivå 1-text. |
| ContinuousArrowProcess | 37 | Används för att visa en tidslinje eller sekventiella steg i en uppgift, process eller arbetsflöde. Fungerar bäst med Nivå 1-text eftersom varje rad av Nivå 1-text visas inne i pilformen. Nivå 2-text visas utanför pilformen. |
| ContinuousBlockProcess | 38 | Används för att visa en progression eller sekventiella steg i en uppgift, process eller arbetsflöde. Fungerar bäst med minimal Nivå 1- och Nivå 2-text. |
| ContinuousCycle | 39 | Används för att representera en fortsättande sekvens av faser, uppgifter eller händelser i ett cirkulärt flöde. Betonar kopplingen mellan alla komponenter. Fungerar bäst endast med Nivå 1-text. |
| ContinuousPictureList | 40 | Används för att visa grupper av sammankopplad information. De cirkulära formerna är avsedda att innehålla bilder. |
| ConvergingArrows | 41 | Används för att visa idéer eller begrepp som konvergerar till en central punkt. Fungerar bäst endast med Nivå 1-text. |
| ConvergingRadial | 42 | Används för att visa relationer mellan begrepp eller komponenter till en central idé i en cykel. Den första raden av Nivå 1-text motsvarar den centrala cirkulära formen och raderna av Nivå 2-text motsvarar de omgivande rektangulära formerna. Oanvänd text visas inte, men förblir tillgänglig om du byter layout. |
| CounterbalanceArrows | 43 | Används för att visa två motstående idéer eller begrepp. Varje av de två första raderna av Nivå 1-text motsvarar en pil och fungerar bra med Nivå 2-text. Oanvänd text visas inte, men förblir tillgänglig om du byter layout. |
| CycleMatrix | 44 | Används för att visa relationen till en central idé i en cyklisk progression. Varje av de fyra första raderna av Nivå 1-text motsvarar ett segment eller en pajform, och Nivå 2-text visas i en rektangulär form bredvid segmentet eller pajformen. Oanvänd text visas inte, men förblir tillgänglig om du byter layout. |
| DescendingBlockList | 45 | Används för att visa grupper av relaterade idéer eller informationslistor. Textformerna minskar i höjd sekventiellt, och Nivå 1-text visas vertikalt. |
| DescendingProcess | 46 | Används för att visa en fallande serie händelser. Den första Nivå 1-texten är högst upp på pilen, och den sista Nivå 1-texten visas längst ner på pilen. Endast de första sju Nivå 1-objekten visas. Fungerar bäst med små till medelstora mängder text. |
| DetailedProcess | 47 | Används med stora mängder Nivå 2-text för att visa en progression genom faser. |
| DivergingArrows | 48 | Används för att visa idéer eller begrepp som utvecklas utåt från en central källa. Fungerar bäst endast med Nivå 1-text. |
| DivergingRadial | 49 | Används för att visa relationer till en central idé i en cykel. Den första Nivå 1-raden av text motsvarar den centrala cirkulära formen. Betonar de omgivande cirklarna snarare än den centrala idén. Oanvänd text visas inte, men förblir tillgänglig om du byter layout. |
| Equation | 50 | Används för att visa sekventiella steg eller uppgifter som illustrerar en plan eller ett resultat. Den sista Nivå 1-raden av text visas efter lika med-tecknet (=). Fungerar bäst endast med Nivå 1-text. |
| FramedTextPicture | 51 | Används för att visa bilder med motsvarande Nivå 1-text som visas i en ram. |
| Funnel | 52 | Används för att visa filtrering av information eller hur delar slås samman till en helhet. Betonar det slutliga resultatet. Kan innehålla upp till fyra rader av Nivå 1-text; den sista av dessa fyra Nivå 1-raderna visas under tratten och de andra raderna motsvarar en cirkulär form. Oanvänd text visas inte, men förblir tillgänglig om du byter layout. |
| Gear | 53 | Används för att visa sammankopplade idéer. Varje av de tre första raderna av Nivå 1-text motsvarar en växelform, och deras motsvarande Nivå 2-text visas i rektanglar bredvid växelformen. Oanvänd text visas inte, men förblir tillgänglig om du byter layout. |
| GridMatrix | 54 | Använd för att visa placeringen av begrepp längs två axlar. Betonar de individuella komponenterna snarare än hela. De första fyra raderna av Level 1-text visas i kvadranterna. Oanvänd text visas inte, men är tillgänglig om du byter layout. |
| GroupedList | 55 | Använd för att visa grupper och undergrupper av information, eller steg och understeg i en uppgift, process eller arbetsflöde. Level 1-text motsvarar de horisontella formerna på toppnivå, och Level 2-text motsvarar vertikala understeg under varje relaterad toppnivåform. Fungerar bra för att betona undergrupper eller understeg, hierarkisk information eller flera informationslistor. |
| HalfCircleOrganizationChart | 56 | Använd för att visa hierarkisk information eller rapporteringsförhållanden i en organisation. Assistentsformerna och Org Chart hängande layouter är tillgängliga med denna layout. |
| HexagonCluster | 57 | Använd för att visa bilder med tillhörande beskrivande text. Små hexagoner markerar bild- och textparet. Fungerar bäst med små mängder text. |
| Hierarchy | 58 | Använd för att visa hierarkiska relationer som utvecklas från topp till botten. |
| HierarchyList | 59 | Använd för att visa hierarkiska relationer som utvecklas över grupper. Kan även användas för att gruppera eller lista information. |
| HorizontalBulletList | 60 | Använd för att visa icke-sekventiella eller grupperade informationslistor. Fungerar bra med stora mängder text. All text har samma betoning och riktning antyds inte. |
| HorizontalHierarchy | 61 | Använd för att visa hierarkiska relationer som utvecklas horisontellt. Fungerar bra för besluts-träd. |
| HorizontalLabeledHierarchy | 62 | Använd för att visa hierarkiska relationer som utvecklas horisontellt och gruppas hierarkiskt. Betonar rubrik- eller Level 1-text. Den första raden av Level 1-text visas i formen i början av hierarkin, och den andra och alla efterföljande rader av Level 1-text visas högst upp på de långa rektanglerna. |
| HorizontalMultiLevelHierarchy | 63 | Använd för att visa stora mängder hierarkisk information som utvecklas horisontellt. Hierarkins topp visas vertikalt. Denna layout stödjer många nivåer i hierarkin. |
| HorizontalOrganizationChart | 64 | Använd för att visa hierarkisk information horisontellt eller rapporteringsförhållanden i en organisation. Assistentsformen och Org Chart hängande layouter är tillgängliga med denna layout. |
| HorizontalPictureList | 65 | Använd för att visa icke-sekventiell eller grupperad information med betoning på relaterade bilder. De övre formerna är avsedda att innehålla bilder. |
| IncreasingArrowsProcess | 66 | Använd för att visa sekventiella och överlappande steg i en process. Begränsad till fem Level 1-objekt. Level 2 kan innehålla stora mängder text. |
| IncreasingCircleProcess | 67 | Använd för att visa en serie steg, där cirkelns insida ökar med varje steg. Begränsad till sju Level 1-steg men obegränsat antal Level 2-objekt. Fungerar bra med stora mängder Level 2-text. |
| InvertedPyramid | 68 | Använd för att visa proportionella, sammanlänkade eller hierarkiska relationer med den största komponenten överst och smalnar av nedåt. Level 1-text visas i pyramids segment och Level 2-text visas i former bredvid varje segment. |
| LabeledHierarchy | 69 | Använd för att visa hierarkiska relationer som utvecklas från topp till botten och grupperas hierarkiskt. Betonar rubrik- eller Level 1-text. Den första raden av Level 1-text visas i formen i början av hierarkin, och alla efterföljande rader av Level 1-text visas till vänster om de långa rektanglerna. |
| LinearVenn | 70 | Använd för att visa överlappande relationer i en sekvens. Fungerar bäst bara med Level 1-text. |
| LinedList | 71 | Använd för att visa stora mängder text uppdelad i kategorier och underkategorier. Fungerar bra med flera textnivåer. Text på samma nivå separeras av linjer. |
| MultidirectionalCycle | 72 | Använd för att representera en fortsättande sekvens av stadier, uppgifter eller händelser som kan inträffa i vilken riktning som helst. |
| NameandTitleOrganizationChart | 73 | Använd för att visa hierarkisk information eller rapporteringsförhållanden i en organisation. För att skriva text i titelrutan, skriv direkt i den mindre rektangulära formen. Assistentsformen och Org Chart hängande layouter är tillgängliga med denna layout. |
| NestedTarget | 74 | Använd för att visa innehållsrelationer. Var och en av de första tre raderna av Level 1-text motsvarar den övre vänstra texten i formerna, och Level 2-text motsvarar de mindre formerna. Fungerar bäst med minimala Level 2-rader av text. Oanvänd text visas inte, men är tillgänglig om du byter layout. |
| NondirectionalCycle | 75 | Använd för att representera en fortsättande sekvens av stadier, uppgifter eller händelser i ett cirkulärt flöde. Varje form har samma viktighetsnivå. Fungerar bra när riktning inte behöver anges. |
| OpposingArrows | 76 | Använd för att visa två motsatta idéer, eller idéer som divergerar från en central punkt. Var och en av de första två raderna av Level 1-text motsvarar en pil. Oanvänd text visas inte, men är tillgänglig om du byter layout. |
| OpposingIdeas | 77 | Använd för att visa två motsatta eller kontrasterande idéer. Kan ha ett eller två Level 1-objekt. Varje Level 1-text kan innehålla flera undernivåer. Fungerar bra med stora mängder text. |
| OrganizationChart | 78 | Använd för att visa hierarkisk information eller rapporteringsförhållanden i en organisation. Assistentsformen och Org Chart hängande layouter är tillgängliga med denna layout. |
| PhasedProcess | 79 | Använd för att visa tre faser av en process. Begränsad till tre Level 1-objekt. De två första Level 1-objekten kan vardera innehålla fyra Level 2-objekt, och det tredje Level 1-objektet kan innehålla ett obegränsat antal Level 2-objekt. Fungerar bäst med små mängder text. |
| PictureAccentBlocks | 80 | Använd för att visa en grupp bilder i block som startar från hörnet. Tillhörande text visas vertikalt. Fungerar bra som accent på titel- eller undertitelsbilder eller för avsnittsbrytningar i ett dokument. |
| PictureAccentList | 81 | Använd för att visa grupperad eller relaterad information. De små formerna i de övre hörnen är avsedda att innehålla bilder. Betonar Level 2-text över Level 1-text, och är ett bra val för stora mängder Level 2-text. |
| PictureAccentProcess | 82 | Använd för att visa sekventiella steg i en uppgift, process eller arbetsflöde. De rektangulära formerna i bakgrunden är avsedda att innehålla bilder. |
| PictureCaptionList | 83 | Använd för att visa icke-sekventiella eller grupperade informationsblock. De övre formerna är avsedda att innehålla bilder och bilder betonas framför text. Fungerar bra för bilder med korta textbeskrivningar. |
| PictureGrid | 84 | Använd för att visa bilder placerade i ett fyrkantigt rutnät. Bäst med en liten mängd Level 1-text, som visas ovanför bilden. |
| PictureLineup | 85 | Använd för att visa en serie bilder sida vid sida. Level 1-text täcker toppen av bilden. Level 2-text visas under bilden. |
| PictureStrips | 86 | Använd för att visa en serie bilder från topp till botten med Level 1-text bredvid varje. |
| PieProcess | 87 | Använd för att visa steg i en process där varje pajskiva ökar i storlek upp till sju former. Level 1-text visas vertikalt. |
| PlusandMinus | 88 | Använd för att visa för- och nackdelar med två idéer. Varje Level 1-text kan innehålla flera undernivåer. Fungerar bra med stora mängder text. Begränsad till två Level 1-objekt. |
| ProcessArrows | 89 | Använd för att visa information som illustrerar en process eller arbetsflöde. Level 1-text visas i de cirkulära formerna och Level 2-text visas i pilformerna. Fungerar bäst för minimal text och för att betona rörelse eller riktning. |
| ProcessList | 90 | Använd för att visa flera grupper av information eller steg och understeg i en uppgift, process eller arbetsflöde. Level 1-text motsvarar de övre horisontella formerna, och Level 2-text motsvarar vertikala understeg under varje relaterad toppnivåform. |
| PyramidList | 91 | Använd för att visa proportionella, sammanlänkade eller hierarkiska relationer. Text visas i de rektangulära formerna ovanpå pyramidbakgrunden. |
| RadialCluster | 92 | Använd för att visa data som relaterar till en central idé eller tema. Den översta Level 1-texten visas i mitten. Level 2-text visas i omgivande former. Kan innehålla upp till sju Level 2-former. Oanvänd text visas inte, men är tillgänglig om du byter layout. Fungerar bäst med små mängder text. |
| RadialCycle | 93 | Använd för att visa relationen till en central idé. Betonar både information i den centrala cirkeln och hur information i den yttre ringen av cirklar bidrar till den centrala idén. Den första Level 1-raden av text motsvarar den centrala cirkeln, och dess Level 2-text motsvarar den yttre ringen av cirklar. Oanvänd text visas inte, men är tillgänglig om du byter layout. |
| RadialList | 94 | Använd för att visa relationer till en central idé i en cykel. Mittformen kan innehålla en bild. Level 1-text visas i de mindre cirklarna och eventuell tillhörande Level 2-text visas bredvid de mindre cirklarna. |
| RadialVenn | 95 | Använd för att visa både överlappande relationer och relationen till en central idé i en cykel. Den första raden av Level 1-text motsvarar den centrala formen och raderna av Level 2-text motsvarar de omgivande cirkulära formerna. Oanvänd text visas inte, men är tillgänglig om du byter layout. |
| RandomToResultProcess | 96 | Använd för att visa, genom en serie steg, hur flera kaotiska idéer kan leda till ett enhetligt mål eller en idé. Stöder flera Level 1-textobjekt, men de första och sista Level 1-motsvarande formerna är fasta. Fungerar bäst med små mängder Level 1-text och medelstora mängder Level 2-text. |
| RepeatingBendingProcess | 97 | Använd för att visa en progression eller sekventiella steg i en uppgift, process eller arbetsflöde. Maximerar både horisontellt och vertikalt displayutrymme för former. |
| ReverseList | 98 | Använd för att växla mellan två objekt. Endast de två första textobjekten visas, och varje objekt kan innehålla en stor mängd text. Fungerar bra för att visa en förändring mellan två objekt eller en förskjutning i ordning. |
| SegmentedCycle | 99 | Använd för att visa en progression eller en sekvens av stadier, uppgifter eller händelser i ett cirkulärt flöde. Betonar de sammankopplade delarna. Var och en av de första sju raderna av Level 1-text motsvarar en kil- eller pajform. Oanvänd text visas inte, men är tillgänglig om du byter layout. |
| SegmentedProcess | 100 | Använd för att visa en progression eller sekventiella steg i en uppgift, process eller arbetsflöde. Betonar Level 2-text, eftersom varje rad visas i en separat form. |
| SegmentedPyramid | 101 | Använd för att visa innehålls-, proportionella eller sammankopplade relationer. De nio första raderna av Level 1-text visas i de triangulära formerna. Oanvänd text visas inte, men är tillgänglig om du byter layout. Fungerar bäst enbart med Level 1-text. |
| SnapshotPictureList | 102 | Använd för att visa bilder med förklarande text. Level 2-text kan visa informationslistor. Fungerar bra med en stor mängd text. |
| SpiralPicture | 103 | Använd för att visa en serie på upp till fem bilder med motsvarande Level 1-rubriker som spiralar in mot mitten. |
| SquareAccentList | 104 | Använd för att visa informationslistor uppdelade i kategorier. Level 2-text visas bredvid en liten fyrkantig form. Fungerar bra med stora mängder Level 2-text. |
| StackedList | 105 | Använd för att visa grupper av information eller steg i en uppgift, process eller arbetsflöde. Cirkelformerna innehåller Level 1-text, och motsvarande rektanglar innehåller Level 2-text. Fungerar bra för många detaljer och minimal Level 1-text. |
| StackedVenn | 106 | Använd för att visa överlappande relationer. Ett bra val för att betona tillväxt eller gradering. Fungerar bäst enbart med Level 1-text. De första sju raderna av Level 1-text motsvarar en cirkulär form. Oanvänd text visas inte, men är tillgänglig om du byter layout. |
| StaggeredProcess | 107 | Använd för att visa en nedåtriktad progression genom steg. Varje av de fem första raderna med Level 1-text motsvarar en rektangel. Oanvänd text visas inte, men finns tillgänglig om du byter layout. |
| StepDownProcess | 108 | Använd för att visa en nedstigande process med flera steg och delsteg. Fungerar bäst med små mängder text. |
| StepUpProcess | 109 | Använd för att visa en stigande serie av steg eller informationslistor. |
| SubStepProcess | 110 | Använd för att visa en flerstegsprocess med delsteg mellan varje förekomst av Level 1-text. Fungerar bäst med små mängder text och är begränsad till sju Level 1-steg. Varje Level 1-steg kan ha obegränsat antal delsteg. |
| TableHierarchy | 111 | Använd för att visa informationsgrupper byggda från topp till botten, samt hierarkierna inom varje grupp. Denna layout innehåller inga anslutande linjer. |
| TableList | 112 | Använd för att visa grupperad eller relaterad information av lika värde. Den första raden med Level 1-text motsvarar den översta formen och dess Level 2-text används för de efterföljande listorna. |
| TargetList | 113 | Använd för att visa sammanlänkad eller överlappande information. Varje av de första sju raderna med Level 1-text visas i den rektangulära formen. Oanvänd text visas inte, men finns tillgänglig om du byter layout. Fungerar väl med både Level 1- och Level 2-text. |
| TextCycle | 114 | Använd för att representera en pågående sekvens av steg, uppgifter eller händelser i ett cirkulärt flöde. Betonar pilarna eller flödet snarare än stegen eller faserna. Fungerar bäst med enbart Level 1-text. |
| TitlePictureLineup | 115 | Använd för att visa en serie bilder där varje har sin egen titel och beskrivning. Level 1-text visas i rutan ovanför bilden. Level 2-text visas under bilden. |
| TitledMatrix | 116 | Använd för att visa relationerna mellan fyra kvadranter och en helhet. Den första raden med Level 1-text motsvarar den centrala formen, och de första fyra raderna med Level 2-text visas i kvadranterna. Oanvänd text visas inte, men finns tillgänglig om du byter layout. |
| TitledPictureAccentList | 117 | Använd för att visa informationslistor med en accentbild för varje Level 2-text. Level 1-text visas i en separat ruta högst upp i listan. |
| TitledPictureBlocks | 118 | Använd för att visa en serie bilder. Level 1-text visas ovanför varje bild. Level 2-text visas åt sidan och något överlappande varje bild. |
| TrapezoidList | 119 | Använd för att visa grupperad eller relaterad information av lika värde. Fungerar bra med stora mängder text. |
| UpwardArrow | 120 | Använd för att visa en progression eller steg som går uppåt i en uppgift, process eller arbetsflöde. Varje av de fem första raderna med Level 1-text motsvarar en punkt på pilen. Fungerar bäst med minimal text. Oanvänd text visas inte, men finns tillgänglig om du byter layout. |
| VerticalAccentList | 121 | Använd för att visa informationslistor. Level 2-text visas i rektangulära former över vertikala chevroner. Betonar Level 2-text framför Level 1-text och är ett bra val för medelstora mängder Level 2-text. |
| VerticalArrowList | 122 | Använd för att visa en progression eller sekventiella steg i en uppgift, process eller arbetsflöde som går mot ett gemensamt mål. Fungerar bra för punktlistor med information. |
| VerticalBendingProcess | 123 | Använd för att visa en progression eller sekventiella steg i en uppgift, process eller arbetsflöde. Maximera både horisontellt och vertikalt skärmutrymme för former. Lägger större vikt vid relationerna mellan formerna än på riktning eller rörelse. |
| VerticalBlockList | 124 | Använd för att visa informationsgrupper eller steg i en uppgift, process eller arbetsflöde. Fungerar bra med stora mängder Level 2-text. Ett bra val för text med en huvudpunkt och flera underpunkter. |
| VerticalBoxList | 125 | Använd för att visa flera informationsgrupper, särskilt grupper med stora mängder Level 2-text. Ett bra val för punktlistor med information. |
| VerticalBulletList | 126 | Använd för att visa icke-sekventiella eller grupperade informationsblock. Fungerar bra för listor med långa rubriker eller toppnivåinformation. |
| VerticalChevronList | 127 | Använd för att visa en progression eller sekventiella steg i en uppgift, process eller arbetsflöde, eller för att betona rörelse eller riktning. Betonar Level 2-text framför Level 1-text och är ett bra val för stora mängder Level 2-text. |
| VerticalCircleList | 128 | Använd för att visa sekventiella eller grupperade data. Fungerar bäst med Level 1-text, som visas bredvid en stor cirkulär form. Lägre textrader separeras med mindre cirkulära former. |
| VerticalCurvedList | 129 | Använd för att visa en böjd informationslista. För att lägga till bilder i accentcirkelformerna, använd en bildfyllning. |
| VerticalEquation | 130 | Använd för att visa sekventiella steg eller uppgifter som visar en plan eller ett resultat. Den sista raden med Level 1-text visas efter pilen. Fungerar bäst med enbart Level 1-text. |
| VerticalPictureAccentList | 131 | Använd för att visa icke-sekventiella eller grupperade informationsblock. De små cirklarna är avsedda att innehålla bilder. |
| VerticalPictureList | 132 | Använd för att visa icke-sekventiella eller grupperade informationsblock. De små formerna till vänster är avsedda att innehålla bilder. |
| VerticalProcess | 133 | Använd för att visa en progression eller sekventiella steg i en uppgift, process eller arbetsflöde från topp till botten. Fungerar bäst med Level 1-text, eftersom det vertikala utrymmet är begränsat. |
| Custom | 134 | Representerar ett [SmartArt](../smartart/) diagram med anpassad layoutmall |
| PictureOrganizationChart | 135 | Använd för att visa hierarkisk information eller rapporteringsrelationer i en organisation, med motsvarande bilder. Assistentsformen och Org Chart-hängande layouter är tillgängliga med denna layout. |

## Se även

* Namnområde [Aspose::Slides::SmartArt](../)
* Bibliotek [Aspose.Slides](../../)