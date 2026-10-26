---
title: SmartArtLayoutType
second_title: Aspose.Sildes for .NET API 參考文件
description: 表示 SmartArt 圖表的版面配置類型。
type: docs
weight: 10620
url: /zh-hant/aspose.slides.smartart/smartartlayouttype/
---
## SmartArtLayoutType 列舉

表示 SmartArt 圖表的版面配置類型。

```csharp
public enum SmartArtLayoutType
```

### 值

| 名稱 | 值 | 說明 |
| --- | --- | --- |
| AccentProcess | `0` | 用於顯示任務、流程或工作流程中的進程、時間軸或連續步驟。適合說明 Level 1 與 Level 2 文字。 |
| AccentedPicture | `1` | 用於顯示中心的照片構想，兩側為相關構想。最上層的 Level 1 文字顯示在中心圖片上。其他 Level 1 形狀的文字顯示在小圓形圖片旁。此版面在沒有文字時也能良好呈現。 |
| AlternatingFlow | `2` | 用於顯示任務、流程或工作流程中的資訊群組或連續步驟。強調資訊群組之間的交互或關係。 |
| AlternatingHexagons | `3` | 用於表示一系列相互關聯的構想。Level 1 文字顯示在六角形內。Level 2 文字顯示在形狀外。 |
| AlternatingPictureBlocks | `4` | 用於從上到下顯示一系列圖片。文字交替出現在圖片的右側或左側。 |
| AlternatingPictureCircles | `5` | 用於顯示帶有文字的一組圖片。相應的文字顯示在中心圓形內，圖片從左至右交替排列。 |
| ArrowRibbon | `6` | 用於顯示相關或對照的概念，帶有某種連結，例如相反的力量。Level 1 文字的前兩行用於箭頭內的文字。未使用的文字不會顯示，但在切換版面時仍可使用。 |
| AscendingPictureAccentProcess | `7` | 用於顯示上升的圖片系列與說明文字。最適合少量文字。 |
| Balance | `8` | 用於比較或顯示兩個構想之間的關係。前兩行 Level 1 文字分別對應於中心點兩側的上方文字。強調 Level 2 文字，且每側最多四個形狀。平衡會向包含較多 Level 2 文字形狀的一側傾斜。未使用的文字不會顯示，但在切換版面時仍可使用。 |
| BasicBendingProcess | `9` | 用於顯示任務、流程或工作流程中的進程或連續步驟。最大化形狀的水平與垂直顯示空間。 |
| BasicBlockList | `10` | 用於顯示非連續或分組的資訊區塊。最大化形狀的水平與垂直顯示空間。 |
| BasicChevronProcess | `11` | 用於顯示進程、時間軸、任務、流程或工作流程中的連續步驟，或強調移動或方向。Level 1 文字顯示在箭頭形狀內，Level 2 文字顯示在箭頭形狀下方。 |
| BasicCycle | `12` | 用於表示循環流中的持續階段、任務或事件序列。強調階段或步驟，而非連接的箭頭或流程。最適合僅使用 Level 1 文字。 |
| BasicMatrix | `13` | 用於在四象限中顯示組件與整體的關係。前四行 Level 1 文字顯示在四象限內。未使用的文字不會顯示，但在切換版面時仍可使用。 |
| BasicPie | `14` | 用於顯示各部份如何構成整體。前七行 Level 1 文字對應於均勻分布的扇形或圓形。最上層的 Level 1 文字形狀顯示在餅圖其餘部分之外以突顯。未使用的文字不會顯示，但在切換版面時仍可使用。 |
| BasicProcess | `15` | 用於顯示任務、流程或工作流程中的進程或連續步驟。 |
| BasicPyramid | `16` | 用於顯示比例、相互關聯或階層關係，最大組件位於底部，向上逐漸收窄。Level 1 文字顯示在金字塔段落中，Level 2 文字顯示在每段旁的形狀內。 |
| BasicRadial | `17` | 用於顯示與中心構想在循環中的關係。第一行 Level 1 文字對應於中心形狀，其 Level 2 文字對應於周圍的圓形。未使用的文字不會顯示，但在切換版面時仍可使用。 |
| BasicTarget | `18` | 用於顯示包含、漸層或階層關係。前五行 Level 1 文字與一個圓形相關聯。未使用的文字不會顯示，但在切換版面時仍可使用。 |
| BasicTimeline | `19` | 用於顯示任務、流程或工作流程中的連續步驟，或顯示時間軸資訊。對於 Level 1 與 Level 2 文字皆表現良好。 |
| BasicVenn | `20` | 用於顯示重疊或相互關聯的關係。前七行 Level 1 文字對應於一個圓形。若 Level 1 文字行數 ≤4，文字位於圓形內；若 >4，文字位於圓形外。未使用的文字不會顯示，但在切換版面時仍可使用。 |
| BendingPictureAccentList | `21` | 用於顯示非連續或分組的資訊區塊。小圓形設計用於容納圖片。對於說明 Level 1 與 Level 2 文字皆表現良好。最大化形狀的水平與垂直顯示空間。 |
| BendingPictureBlocks | `22` | 用於顯示一系列圖片。底角的方框可容納少量文字。 |
| BendingPictureCaption | `23` | 用於顯示一連串順序圖片。底角的方框可容納少量文字。 |
| BendingPictureCaptionList | `24` | 用於顯示一系列圖片。標題與說明顯示在每張圖片下方的說明框中。 |
| BendingPictureSemiTransparentText | `25` | 用於顯示一系列圖片。半透明方框覆蓋圖片的下部，包含所有層級的文字。 |
| BlockCycle | `26` | 用於表示循環流中的持續階段、任務或事件序列。強調階段或步驟，而非連接的箭頭或流程。 |
| BubblePictureList | `27` | 用於顯示一系列圖片。可容納最多八張 Level 1 圖片。未使用的文字與圖片不會顯示，但在切換版面時仍可使用。最適合少量文字。 |
| CaptionedPictures | `28` | 用於顯示帶有多層文字的圖片。最適合少量 Level 1 文字與中等量 Level 2 文字。 |
| ChevronList | `29` | 用於顯示組成整體工作流程的多個流程的進程。亦可用於說明對照的流程。Level 1 文字對應於左側的第一個箭頭形狀，Level 2 文字對應於每個包含 Level 1 文字的形狀的水平子步驟。 |
| CircleAccentTimeline | `30` | 用於顯示一系列事件或時間軸資訊。Level 1 文字出現在較大圓形旁，Level 2 文字出現在較小圓形旁。 |
| CircleArrowProcess | `31` | 用於顯示每個項目都有支援文字的連續項目。此圖表最適合少量 Level 1 文字。 |
| CirclePictureHierarchy | `32` | 用於顯示組織中的階層資訊或匯報關係。圖片出現在圓形內，對應的文字出現在圖片旁。 |
| CircleRelationship | `33` | 用於顯示與中心構想的關係或來自中心構想的關係。Level 2 文字以非連續方式加入，且限制為五個項目。只能有一個 Level 1 項目。 |
| CircularBendingProcess | `34` | 用於顯示任務、流程或工作流程中較長或非線性的序列或步驟。最適合僅使用 Level 1 文字。最大化形狀的水平與垂直顯示空間。 |
| CircularPictureCallout | `35` | 用於顯示中心構想及其子構想或相關項目。第一張圖片的文字覆蓋圖片的下部。其他 Level 1 形狀的相應文字顯示在小圓形圖片旁。此圖表在沒有文字時也能良好呈現。 |
| ClosedChevronProcess | `36` | 用於顯示任務、流程或工作流程中的進程、時間軸或連續步驟，或強調移動或方向。可用於強調起始形狀中的資訊。最適合僅使用 Level 1 文字。 |
| ContinuousArrowProcess | `37` | 用於顯示時間軸或任務、流程或工作流程中的連續步驟。最適合使用 Level 1 文字，因為每行 Level 1 文字顯示在箭頭形狀內。Level 2 文字顯示在箭頭形狀外。 |
| ContinuousBlockProcess | `38` | 用於顯示任務、流程或工作流程中的進程或連續步驟。最適合最少量的 Level 1 與 Level 2 文字。 |
| ContinuousCycle | `39` | 用於表示循環流中的持續階段、任務或事件序列。強調所有組件之間的連結。最適合僅使用 Level 1 文字。 |
| ContinuousPictureList | `40` | 用於顯示相互關聯的資訊群組。圓形設計用於容納圖片。 |
| ConvergingArrows | `41` | 用於顯示匯聚至中心點的概念或想法。最適合僅使用 Level 1 文字。 |
| ConvergingRadial | `42` | 用於顯示概念或組件相對於中心構想在循環中的關係。第一行 Level 1 文字對應於中心圓形，Level 2 文字對應於周圍的矩形。未使用的文字不會顯示，但在切換版面時仍可使用。 |
| CounterbalanceArrows | `43` | 用於顯示兩個相對的概念。前兩行 Level 1 文字各對應一個箭頭，並且與 Level 2 文字搭配良好。未使用的文字不會顯示，但在切換版面時仍可使用。 |
| CycleMatrix | `44` | 用於顯示在循環進程中相對於中心構想的關係。前四行 Level 1 文字對應於扇形或餅形，Level 2 文字顯示在扇形或餅形旁的矩形內。未使用的文字不會顯示，但在切換版面時仍可使用。 |
| DescendingBlockList | `45` | 用於顯示相關構想或資訊清單的群組。文字形狀依序降低高度，Level 1 文字垂直排列。 |
| DescendingProcess | `46` | 用於顯示下降的事件序列。第一個 Level 1 文字位於箭頭頂部，最後一個 Level 1 文字位於箭頭底部。僅顯示前七個 Level 1 項目。最適合少至中量文字。 |
| DetailedProcess | `47` | 用於大量 Level 2 文字，以顯示階段性的進程。 |
| DivergingArrows | `48` | 用於顯示從中心來源向外擴展的概念或想法。最適合僅使用 Level 1 文字。 |
| DivergingRadial | `49` | 用於顯示相對於中心構想在循環中的關係。第一行 Level 1 文字對應於中心圓形。強調周圍的圓形而非中心構想。未使用的文字不會顯示，但在切換版面時仍可使用。 |
| Equation | `50` | 用於顯示描述計畫或結果的連續步驟或任務。最後一行 Level 1 文字出現在等號 (=) 之後。最適合僅使用 Level 1 文字。 |
| FramedTextPicture | `51` | 用於顯示帶有框架內 Level 1 文字的圖片。 |
| Funnel | `52` | 用於顯示資訊的篩選或部件合併成整體的過程。強調最終結果。可容納最多四行 Level 1 文字；第四行顯示在漏斗下方，其餘行對應於圓形。未使用的文字不會顯示，但在切換版面時仍可使用。 |
| Gear | `53` | 用於顯示相互鎖緊的概念。前三行 Level 1 文字對應於齒輪形狀，其相應的 Level 2 文字顯示在齒輪旁的矩形內。未使用的文字不會顯示，但在切換版面時仍可使用。 |
| GridMatrix | `54` | 用於顯示概念在兩個軸向上的位置。強調個別組件而非整體。前四行 Level 1 文字顯示在四象限內。未使用的文字不會顯示，但在切換版面時仍可使用。 |
| GroupedList | `55` | 用於顯示資訊的群組與子群組，或任務、流程或工作流程中的步驟與子步驟。Level 1 文字對應於頂層水平形狀，Level 2 文字對應於每個相關頂層形狀下的垂直子步驟。非常適合強調子群組或子步驟、階層資訊或多個資訊清單。 |
| HalfCircleOrganizationChart | `56` | 用於顯示組織中的階層資訊或匯報關係。此版面提供助理形狀與組織圖懸掛版面。 |
| HexagonCluster | `57` | 用於顯示帶有說明文字的圖片。小六角形表示圖片與文字的配對。最適合少量文字。 |
| Hierarchy | `58` | 用於顯示自上而下的階層關係。 |
| HierarchyList | `59` | 用於顯示跨群組的階層關係。也可用於分組或列舉資訊。 |
| HorizontalBulletList | `60` | 用於顯示非連續或分組的資訊清單。適合大量文字。所有文字具有相同的強調層級，且不暗示方向。 |
| HorizontalHierarchy | `61` | 用於顯示水平進行的階層關係。適合決策樹。 |
| HorizontalLabeledHierarchy | `62` | 用於顯示水平進行且具階層分組的階層關係。強調標題或 Level 1 文字。第一行 Level 1 文字顯示在階層起始形狀，之後的所有 Level 1 文字顯示在高矩形的上方。 |
| HorizontalMultiLevelHierarchy | `63` | 用於顯示大量水平進行的階層資訊。階層的頂部垂直顯示。此版面支援多層階層。 |
| HorizontalOrganizationChart | `64` | 用於水平顯示組織中的階層資訊或匯報關係。此版面提供助理形狀與組織圖懸掛版面。 |
| HorizontalPictureList | `65` | 用於顯示非連續或分組的資訊，強調相關圖片。頂部形狀設計用於容納圖片。 |
| IncreasingArrowsProcess | `66` | 用於顯示流程中連續且交疊的步驟。限制為五個 Level 1 項目。Level 2 可容納大量文字。 |
| IncreasingCircleProcess | `67` | 用於顯示一系列步驟，隨著每一步圓形內部逐漸增大。限制為七個 Level 1 步驟，Level 2 項目不限。對大量 Level 2 文字表現良好。 |
| InvertedPyramid | `68` | 用於顯示比例、相互關聯或階層關係，最大組件位於頂部，向下逐漸收窄。Level 1 文字顯示在金字塔段落中，Level 2 文字顯示在每段旁的形狀內。 |
| LabeledHierarchy | `69` | 用於自上而下且具階層分組的階層關係。強調標題或 Level 1 文字。第一行 Level 1 文字顯示在階層起始形狀，所有後續 Level 1 文字顯示在長矩形的左側。 |
| LinearVenn | `70` | 用於顯示序列中的重疊關係。最適合僅使用 Level 1 文字。 |
| LinedList | `71` | 用於顯示大量文字，分為類別與子類別。對多層文字表現良好。相同層級的文字以線條分隔。 |
| MultidirectionalCycle | `72` | 用於表示可任意方向發生的持續階段、任務或事件序列。 |
| NameandTitleOrganizationChart | `73` | 用於顯示組織中的階層資訊或匯報關係。若要在標題框內輸入文字，直接在較小的矩形形狀內鍵入。此版面提供助理形狀與組織圖懸掛版面。 |
| NestedTarget | `74` | 用於顯示包含關係。前三行 Level 1 文字分別對應於形狀左上角的文字，Level 2 文字對應於較小的形狀。最適合最少量的 Level 2 文字。未使用的文字不會顯示，但在切換版面時仍可使用。 |
| NondirectionalCycle | `75` | 用於表示循環流中的持續階段、任務或事件序列。每個形狀具有相同的重要性。適合不需指示方向的情況。 |
| OpposingArrows | `76` | 用於顯示兩個相對的構想，或從中心點發散的構想。前兩行 Level 1 文字各對應一個箭頭。未使用的文字不會顯示，但在切換版面時仍可使用。 |
| OpposingIdeas | `77` | 用於顯示兩個相對或對照的構想。可包含一或兩個 Level 1 項目。每個 Level 1 文字可包含多個子層級。對大量文字表現良好。 |
| OrganizationChart | `78` | 用於顯示組織中的階層資訊或匯報關係。此版面提供助理形狀與組織圖懸掛版面。 |
| PhasedProcess | `79` | 用於顯示流程的三個階段。限制為三個 Level 1 項目。前兩個 Level 1 項目各可包含四個 Level 2 項目，第三個 Level 1 項目可包含不限數量的 Level 2 項目。最適合少量文字。 |
| PictureAccentBlocks | `80` | 用於從角落開始以區塊方式顯示一組圖片。相應文字垂直排列。非常適合作為標題或副標題投影片的強調，或文件的分節標記。 |
| PictureAccentList | `81` | 用於顯示分組或相關資訊。左上角的小形狀設計用於容納圖片。強調 Level 2 文字於 Level 1 文字之上，適合大量 Level 2 文字。 |
| PictureAccentProcess | `82` | 用於顯示任務、流程或工作流程中的連續步驟。背景的矩形形狀設計用於容納圖片。 |
| PictureCaptionList | `83` | 用於顯示非連續或分組的資訊區塊。頂部形狀設計用於容納圖片，圖片相對於文字更受強調。非常適合帶有簡短文字說明的圖片。 |
| PictureGrid | `84` | 用於在方形網格上排列圖片。最適合少量的 Level 1 文字，文字顯示在圖片上方。 |
| PictureLineup | `85` | 用於顯示一系列並列的圖片。Level 1 文字覆蓋圖片上方，Level 2 文字出現在圖片下方。 |
| PictureStrips | `86` | 用於從上到下顯示一系列圖片，Level 1 文字位於每張圖片旁。 |
| PieProcess | `87` | 用於顯示流程步驟，每個餅圖切片可增加至七個形狀。Level 1 文字垂直排列。 |
| PlusandMinus | `88` | 用於顯示兩個構想的優缺點。每個 Level 1 文字可包含多個子層級。對大量文字表現良好。限制為兩個 Level 1 項目。 |
| ProcessArrows | `89` | 用於說明流程或工作流程的資訊。Level 1 文字出現在圓形，Level 2 文字出現在箭頭形狀。最適合最少文字，且強調移動或方向。 |
| ProcessList | `90` | 用於顯示多組資訊或任務、流程或工作流程中的步驟與子步驟。Level 1 文字對應於頂部水平形狀，Level 2 文字對應於每個相關頂層形狀下的垂直子步驟。 |
| PyramidList | `91` | 用於顯示比例、相互關聯或階層關係。文字出現在金字塔背景上方的矩形形狀內。 |
| RadialCluster | `92` | 用於顯示與中心構想或主題相關的資料。頂部的 Level 1 文字出現在中心。Level 2 文字出現在周圍形狀。可容納最多七個 Level 2 形狀。未使用的文字不會顯示，但在切換版面時仍可使用。最適合少量文字。 |
| RadialCycle | `93` | 用於顯示與中心構想的關係。強調中心圓形內的資訊以及外圍圓環對中心構想的貢獻。第一行 Level 1 文字對應於中心圓形，其 Level 2 文字對應於外圍圓環。未使用的文字不會顯示，但在切換版面時仍可使用。 |
| RadialList | `94` | 用於顯示相對於中心構想的循環關係。中心形狀可容納圖片。Level 1 文字出現在較小圓形，相關的 Level 2 文字出現在小圓形旁。 |
| RadialVenn | `95` | 用於同時顯示重疊關係與相對於中心構想的循環關係。第一行 Level 1 文字對應於中心形狀，Level 2 文字行對應於周圍的圓形。未使用的文字不會顯示，但在切換版面時仍可使用。 |
| RandomToResultProcess | `96` | 用於透過一系列步驟說明多個混亂構想如何產生成統一目標或構想。支援多個 Level 1 文字項目，但第一與最後的 Level 1 形狀固定。最適合少量 Level 1 文字與中等量 Level 2 文字。 |
| RepeatingBendingProcess | `97` | 用於顯示任務、流程或工作流程中的進程或連續步驟。最大化形狀的水平與垂直顯示空間。 |
| ReverseList | `98` | 用於在兩個項目之間切換。僅顯示前兩個文字項目，每個項目可包含大量文字。適合顯示兩項之間的變化或順序的轉換。 |
| SegmentedCycle | `99` | 用於在循環流中顯示進程或階段、任務、事件的序列。強調相互關聯的片段。前七行 Level 1 文字各對應於一個扇形或餅形。未使用的文字不會顯示，但在切換版面時仍可使用。 |
| SegmentedProcess | `100` | 用於顯示任務、流程或工作流程中的進程或連續步驟。強調 Level 2 文字，因為每行文字出現在單獨的形狀內。 |
| SegmentedPyramid | `101` | 用於顯示包含、比例或相互關聯的關係。前九行 Level 1 文字出現在三角形形狀內。未使用的文字不會顯示，但在切換版面時仍可使用。最適合僅使用 Level 1 文字。 |
| SnapshotPictureList | `102` | 用於顯示帶說明文字的圖片。Level 2 文字可顯示資訊清單。對大量文字表現良好。 |
| SpiralPicture | `103` | 用於顯示最多五張圖片，對應的 Level 1 標題呈螺旋形向中心收斂。 |
| SquareAccentList | `104` | 用於顯示分成類別的資訊清單。Level 2 文字顯示在小方形旁。對大量 Level 2 文字表現良好。 |
| StackedList | `105` | 用於顯示任務、流程或工作流程中的資訊群組或步驟。圓形形狀容納 Level 1 文字，對應的矩形容納 Level 2 文字。對大量細節與最少 Level 1 文字表現良好。 |
| StackedVenn | `106` | 用於顯示重疊關係。適合強調成長或漸層。最適合僅使用 Level 1 文字。前七行 Level 1 文字對應於圓形。未使用的文字不會顯示，但在切換版面時仍可使用。 |
| StaggeredProcess | `107` | 用於顯示向下的階段性進程。前五行 Level 1 文字各對應於一個矩形。未使用的文字不會顯示，但在切換版面時仍可使用。 |
| StepDownProcess | `108` | 用於顯示多步驟與子步驟的下降流程。最適合少量文字。 |
| StepUpProcess | `109` | 用於顯示上升的步驟系列或資訊清單。 |
| SubStepProcess | `110` | 用於顯示每個 Level 1 文字之間有子步驟的多步驟流程。最適合少量文字，且限制為七個 Level 1 步驟。每個 Level 1 步驟可有無限子步驟。 |
| TableHierarchy | `111` | 用於顯示由上而下構建的資訊群組及其層級。此版面不含連接線。 |
| TableList | `112` | 用於顯示等值的分組或相關資訊。第一行 Level 1 文字對應於頂部形狀，其 Level 2 文字用於隨後的清單。 |
| TargetList | `113` | 用於顯示相互關聯或重疊的資訊。前七行 Level 1 文字出現在矩形形狀內。未使用的文字不會顯示，但在切換版面時仍可使用。對 Level 1 與 Level 2 文字皆表現良好。 |
| TextCycle | `114` | 用於表示循環流中的持續階段、任務或事件序列。強調箭頭或流程而非階段或步驟。最適合僅使用 Level 1 文字。 |
| TitlePictureLineup | `115` | 用於顯示每張圖片都有其標題與說明的系列圖片。Level 1 文字顯示在圖片上方的方框內，Level 2 文字顯示在圖片下方。 |
| TitledMatrix | `116` | 用於顯示四個象限與整體的關係。第一行 Level 1 文字對應於中心形狀，前四行 Level 2 文字出現在四象限內。未使用的文字不會顯示，但在切換版面時仍可使用。 |
| TitledPictureAccentList | `117` | 用於顯示每個 Level 2 文字都有一張強調圖片的資訊清單。Level 1 文字顯示在清單頂部的獨立方框內。 |
| TitledPictureBlocks | `118` | 用於顯示一系列圖片。Level 1 文字出現在每張圖片上方。Level 2 文字出現在側面且稍微覆蓋每張圖片。 |
| TrapezoidList | `119` | 用於顯示等值的分組或相關資訊。對大量文字表現良好。 |
| UpwardArrow | `120` | 用於顯示任務、流程或工作流程中向上趨勢的進程或步驟。前五行 Level 1 文字各對應於箭頭上的一個點。最適合最少文字。未使用的文字不會顯示，但在切換版面時仍可使用。 |
| VerticalAccentList | `121` | 用於顯示資訊清單。Level 2 文字出現在垂直尖角形上的矩形內。強調 Level 2 文字於 Level 1 文字之上，適合中等量的 Level 2 文字。 |
| VerticalArrowList | `122` | 用於顯示向共同目標前進的任務、流程或工作流程的連續步驟。適合項目符號式資訊清單。 |
| VerticalBendingProcess | `123` | 用於顯示任務、流程或工作流程中的進程或連續步驟。最大化形狀的水平與垂直顯示空間。較強調形狀之間的相互關係，而非方向或移動。 |
| VerticalBlockList | `124` | 用於顯示任務、流程或工作流程中的資訊群組或步驟。對大量 Level 2 文字表現良好。適合有主旨與多個子要點的文字。 |
| VerticalBoxList | `125` | 用於顯示多組資訊，特別是包含大量 Level 2 文字的群組。適合項目符號式資訊清單。 |
| VerticalBulletList | `126` | 用於顯示非連續或分組的資訊區塊。適合標題較長或最高層級資訊的清單。 |
| VerticalChevronList | `127` | 用於顯示任務、流程或工作流程中的進程或連續步驟，或強調移動或方向。強調 Level 2 文字於 Level 1 文字之上，適合大量 Level 2 文字。 |
| VerticalCircleList | `128` | 用於顯示連續或分組的資料。最適合顯示 Level 1 文字，文字顯示於大型圓形旁。較低層級的文字以較小圓形分隔。 |
| VerticalCurvedList | `129` | 用於顯示彎曲的資訊清單。若要將圖片加入強調圓形，請套用圖片填充。 |
| VerticalEquation | `130` | 用於顯示描述計畫或結果的連續步驟或任務。最後一行 Level 1 文字出現在箭頭之後。最適合僅使用 Level 1 文字。 |
| VerticalPictureAccentList | `131` | 用於顯示非連續或分組的資訊區塊。小圓形設計用於容納圖片。 |
| VerticalPictureList | `132` | 用於顯示非連續或分組的資訊區塊。左側的小形狀設計用於容納圖片。 |
| VerticalProcess | `133` | 用於自上而下顯示任務、流程或工作流程的進程或連續步驟。最適合僅使用 Level 1 文字，因為垂直空間有限。 |
| Custom | `134` | 表示具有自訂版面模板的 SmartArt 圖表 |
| PictureOrganizationChart | `135` | 用於顯示組織中的階層資訊或匯報關係，並搭配相應圖片。此版面提供助理形狀與組織圖懸掛版面。 |

### 另請參閱

* 命名空間 [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* 組件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->