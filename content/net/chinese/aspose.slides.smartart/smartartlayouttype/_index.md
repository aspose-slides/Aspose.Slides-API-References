---
title: SmartArtLayoutType
second_title: Aspose.Sildes for .NET API 参考
description: 表示 SmartArt 图表的布局类型。
type: docs
weight: 10620
url: /zh/aspose.slides.smartart/smartartlayouttype/
---
## SmartArtLayoutType 枚举

表示 SmartArt 图表的布局类型。

```csharp
public enum SmartArtLayoutType
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| AccentProcess | `0` | 用于展示任务、流程或工作流中的进展、时间线或顺序步骤。非常适合演示 Level 1 和 Level 2 文本。 |
| AccentedPicture | `1` | 用于展示中心的摄影概念及其旁边的相关概念。顶部的 Level 1 文本显示在中心图片上方。其他 Level 1 形状的对应文本显示在小圆形图片旁边。该布局在没有文本时也能良好呈现。 |
| AlternatingFlow | `2` | 用于展示任务、流程或工作流中信息组或顺序步骤。强调信息组之间的交互或关系。 |
| AlternatingHexagons | `3` | 用于表示一系列相互关联的想法。Level 1 文本显示在六边形内部。Level 2 文本显示在形状外部。 |
| AlternatingPictureBlocks | `4` | 用于从上到下展示一系列图片。文本交替显示在图片的右侧或左侧。 |
| AlternatingPictureCircles | `5` | 用于展示一组带有文本的图片。对应的文本显示在中心圆形中，图片从左到右交替排列。 |
| ArrowRibbon | `6` | 用于展示相关或对比概念以及它们之间的联系，如相对的力量。Level 1 文本的前两行用于箭头中的文本。未使用的文本不显示，但在切换布局时仍可用。 |
| AscendingPictureAccentProcess | `7` | 用于展示上升系列的图片及说明性文本。最适合少量文本。 |
| Balance | `8` | 用于比较或显示两个想法之间的关系。Level 1 文本的前两行对应中心点两侧顶部的文本。强调 Level 2 文本，且每侧最多四个形状。平衡会倾向于包含更多 Level 2 文本的那一侧。未使用的文本不显示，但在切换布局时仍可用。 |
| BasicBendingProcess | `9` | 用于展示任务、流程或工作流中的进展或顺序步骤。最大化形状的水平和垂直显示空间。 |
| BasicBlockList | `10` | 用于展示非顺序或分组的信息块。最大化形状的水平和垂直显示空间。 |
| BasicChevronProcess | `11` | 用于展示进展、时间线、任务、流程或工作流中的顺序步骤，或强调移动或方向。Level 1 文本显示在箭头形状内部，Level 2 文本显示在箭头形状下方。 |
| BasicCycle | `12` | 用于表示循环流中阶段、任务或事件的连续序列。强调阶段或步骤，而非连接的箭头或流。最适合仅使用 Level 1 文本。 |
| BasicMatrix | `13` | 用于在象限中显示组件相对于整体的关系。前四行 Level 1 文本显示在象限中。未使用的文本不显示，但在切换布局时仍可用。 |
| BasicPie | `14` | 用于展示各部分如何组成整体。前七行 Level 1 文本对应均匀分布的楔形或饼形。顶部的 Level 1 文本形状显示在饼的其余部分之外以示强调。未使用的文本不显示，但在切换布局时仍可用。 |
| BasicProcess | `15` | 用于展示任务、流程或工作流中的进展或顺序步骤。 |
| BasicPyramid | `16` | 用于展示比例、相互关联或层级关系，底部为最大组件并向上收窄。Level 1 文本显示在金字塔段中，Level 2 文本显示在每段旁边的形状中。 |
| BasicRadial | `17` | 用于展示相对于中心概念的循环关系。第一行 Level 1 文本对应中心形状，其 Level 2 文本对应周围的圆形。未使用的文本不显示，但在切换布局时仍可用。 |
| BasicTarget | `18` | 用于展示包含、渐变或层级关系。前五行 Level 1 文本与一个圆形关联。未使用的文本不显示，但在切换布局时仍可用。 |
| BasicTimeline | `19` | 用于展示任务、流程或工作流中的顺序步骤，或展示时间线信息。对 Level 1 和 Level 2 文本均表现良好。 |
| BasicVenn | `20` | 用于展示重叠或相互关联的关系。前七行 Level 1 文本对应一个圆形。若 Level 1 文本行数不超过四行，文本位于圆形内部；若超过四行，文本位于圆形外部。未使用的文本不显示，但在切换布局时仍可用。 |
| BendingPictureAccentList | `21` | 用于展示非顺序或分组的信息块。小圆形设计用于容纳图片。对 Level 1 和 Level 2 文本均表现良好。最大化形状的水平和垂直显示空间。 |
| BendingPictureBlocks | `22` | 用于展示一系列图片。覆盖底部角落的框可以容纳少量文本。 |
| BendingPictureCaption | `23` | 用于展示顺序系列的图片。覆盖底部角落的框可以容纳少量文本。 |
| BendingPictureCaptionList | `24` | 用于展示一系列图片。标题和描述出现在每张图片下方的标注形状中。 |
| BendingPictureSemiTransparentText | `25` | 用于展示一系列图片。半透明框覆盖图片的下部并包含所有层级的文本。 |
| BlockCycle | `26` | 用于表示循环流中阶段、任务或事件的连续序列。强调阶段或步骤，而非连接的箭头或流。 |
| BubblePictureList | `27` | 用于展示一系列图片。可容纳最多八个 Level 1 图片。未使用的文本和图片不显示，但在切换布局时仍可用。最适合少量文本。 |
| CaptionedPictures | `28` | 用于展示带有多层文本的图片。最适合少量 Level 1 文本和中等量的 Level 2 文本。 |
| ChevronList | `29` | 用于展示组成整体工作流的多个过程的进展，也可用于对比过程。Level 1 文本对应左侧的第一个箭头形状，Level 2 文本对应每个包含 Level 1 文本的形状的水平子步骤。 |
| CircleAccentTimeline | `30` | 用于展示一系列事件或时间线信息。Level 1 文本出现在较大圆形旁边，Level 2 文本出现在较小圆形旁边。 |
| CircleArrowProcess | `31` | 用于展示每项都有支持文本的顺序项目。该图表最适合少量 Level 1 文本。 |
| CirclePictureHierarchy | `32` | 用于展示组织中的层级信息或汇报关系。图片出现在圆形中，相关文本出现在图片旁边。 |
| CircleRelationship | `33` | 用于展示相对于中心概念的关系。Level 2 文本以非顺序方式添加，且限于五项。只能有一个 Level 1 项。 |
| CircularBendingProcess | `34` | 用于展示任务、流程或工作流中较长或非线性的序列或步骤。最适合仅使用 Level 1 文本。最大化形状的水平和垂直显示空间。 |
| CircularPictureCallout | `35` | 用于展示中心概念及其子概念或相关项。第一张图片的文本覆盖图片下部。其他 Level 1 形状的对应文本出现在小圆形图片旁边。该图表在没有文本时也表现良好。 |
| ClosedChevronProcess | `36` | 用于展示任务、流程或工作流中的进展、时间线或顺序步骤，或强调移动或方向。可用于强调起始形状中的信息。最适合仅使用 Level 1 文本。 |
| ContinuousArrowProcess | `37` | 用于展示任务、流程或工作流中的时间线或顺序步骤。最适合使用 Level 1 文本，因为每行 Level 1 文本显示在箭头形状内部。Level 2 文本显示在箭头形状外部。 |
| ContinuousBlockProcess | `38` | 用于展示任务、流程或工作流中的进展或顺序步骤。最适合极少的 Level 1 和 Level 2 文本。 |
| ContinuousCycle | `39` | 用于表示循环流中阶段、任务或事件的连续序列。强调所有组件之间的连接。最适合仅使用 Level 1 文本。 |
| ContinuousPictureList | `40` | 用于展示相互关联的信息组。圆形设计用于容纳图片。 |
| ConvergingArrows | `41` | 用于展示汇聚到中心点的想法或概念。最适合仅使用 Level 1 文本。 |
| ConvergingRadial | `42` | 用于展示概念或组件相对于中心概念的循环关系。第一行 Level 1 文本对应中心圆形，Level 2 文本对应周围的矩形形状。未使用的文本不显示，但在切换布局时仍可用。 |
| CounterbalanceArrows | `43` | 用于展示两个相对的想法或概念。前两行 Level 1 文本各对应一个箭头，并能很好地配合 Level 2 文本。未使用的文本不显示，但在切换布局时仍可用。 |
| CycleMatrix | `44` | 用于展示相对于中心概念的循环进展关系。前四行 Level 1 文本对应楔形或饼形，Level 2 文本出现在楔形或饼形旁边的矩形中。未使用的文本不显示，但在切换布局时仍可用。 |
| DescendingBlockList | `45` | 用于展示相关想法或信息列表。文本形状按高度递减，Level 1 文本垂直排列。 |
| DescendingProcess | `46` | 用于展示下降系列的事件。第一行 Level 1 文本位于箭头顶部，最后一行 Level 1 文本位于箭头底部。仅显示前七个 Level 1 项。最适合少量到中等量的文本。 |
| DetailedProcess | `47` | 与大量 Level 2 文本一起使用，以展示阶段性的进展。 |
| DivergingArrows | `48` | 用于展示从中心源向外扩散的想法或概念。最适合仅使用 Level 1 文本。 |
| DivergingRadial | `49` | 用于展示相对于中心概念的循环关系。第一行 Level 1 文本对应中心圆形。强调周围的圆形而非中心概念。未使用的文本不显示，但在切换布局时仍可用。 |
| Equation | `50` | 用于展示表示计划或结果的顺序步骤或任务。最后一行 Level 1 文本出现在等号 (=) 之后。最适合仅使用 Level 1 文本。 |
| FramedTextPicture | `51` | 用于展示带有对应 Level 1 文本并显示在框中的图片。 |
| Funnel | `52` | 用于展示信息过滤或部分合并为整体的过程。强调最终结果。可容纳最多四行 Level 1 文本；最后一行显示在漏斗下方，其他行对应圆形。未使用的文本不显示，但在切换布局时仍可用。 |
| Gear | `53` | 用于展示相互锁定的想法。前三行 Level 1 文本对应齿轮形状，其对应的 Level 2 文本出现在齿轮旁边的矩形中。未使用的文本不显示，但在切换布局时仍可用。 |
| GridMatrix | `54` | 用于展示概念在两个轴上的排列。强调各个组件而非整体。前四行 Level 1 文本出现在象限中。未使用的文本不显示，但在切换布局时仍可用。 |
| GroupedList | `55` | 用于展示信息组和子组，或任务、流程或工作流的步骤和子步骤。Level 1 文本对应顶部水平形状，Level 2 文本对应每个相关顶部形状下方的垂直子步骤。非常适合强调子组或子步骤、层级信息或多个信息列表。 |
| HalfCircleOrganizationChart | `56` | 用于展示组织中的层级信息或汇报关系。该布局提供助理形状和组织图悬挂布局。 |
| HexagonCluster | `57` | 用于展示带有说明性文本的图片。小六边形表示图片和文本对。最适合少量文本。 |
| Hierarchy | `58` | 用于展示从上到下的层级关系。 |
| HierarchyList | `59` | 用于展示跨组的层级关系，也可用于分组或列出信息。 |
| HorizontalBulletList | `60` | 用于展示非顺序或分组的信息列表。对大量文本表现良好。所有文本具有相同的强调程度，且不暗示方向。 |
| HorizontalHierarchy | `61` | 用于展示水平进展的层级关系。对决策树表现良好。 |
| HorizontalLabeledHierarchy | `62` | 用于水平进展并按层级分组的层级关系。强调标题或 Level 1 文本。第一行 Level 1 文本出现在层级起始形状中，后续的 Level 1 文本出现在高矩形顶部。 |
| HorizontalMultiLevelHierarchy | `63` | 用于水平进展的大量层级信息。层级顶部垂直显示。此布局支持多层级。 |
| HorizontalOrganizationChart | `64` | 用于水平展示组织层级信息或汇报关系。该布局提供助理形状和组织图悬挂布局。 |
| HorizontalPictureList | `65` | 用于展示非顺序或分组的信息，重点在相关图片。顶部形状设计用于容纳图片。 |
| IncreasingArrowsProcess | `66` | 用于展示过程中的顺序和重叠步骤。限于五个 Level 1 项。Level 2 可容纳大量文本。 |
| IncreasingCircleProcess | `67` | 用于展示一系列步骤，圆心随每一步增大。限于七个 Level 1 步骤，但 Level 2 项目不限。对大量 Level 2 文本表现良好。 |
| InvertedPyramid | `68` | 用于展示比例、相互关联或层级关系，最大组件位于顶部并向下收窄。Level 1 文本显示在金字塔段中，Level 2 文本显示在每段旁边的形状中。 |
| LabeledHierarchy | `69` | 用于从上到下并按层级分组的层级关系。强调标题或 Level 1 文本。第一行 Level 1 文本出现在层级起始形状中，所有后续的 Level 1 文本出现在长矩形左侧。 |
| LinearVenn | `70` | 用于展示序列中的重叠关系。最适合仅使用 Level 1 文本。 |
| LinedList | `71` | 用于将大量文本按类别和子类别划分。对多层级文本表现良好。相同层级的文本以线条分隔。 |
| MultidirectionalCycle | `72` | 用于表示可以任意方向发生的阶段、任务或事件的连续序列。 |
| NameandTitleOrganizationChart | `73` | 用于展示组织中的层级信息或汇报关系。要在标题框中输入文本，请直接在较小的矩形形状中键入。该布局提供助理形状和组织图悬挂布局。 |
| NestedTarget | `74` | 用于展示包含关系。前三行 Level 1 文本对应形状左上角的文本，Level 2 文本对应较小的形状。最适合极少的 Level 2 文本行。未使用的文本不显示，但在切换布局时仍可用。 |
| NondirectionalCycle | `75` | 用于表示循环流中阶段、任务或事件的连续序列。每个形状具有相同的重要性。适用于不需指示方向的情况。 |
| OpposingArrows | `76` | 用于展示两个对立的想法或从中心点发散的想法。前两行 Level 1 文本各对应一个箭头。未使用的文本不显示，但在切换布局时仍可用。 |
| OpposingIdeas | `77` | 用于展示两个相对或对比的想法。可包含一个或两个 Level 1 项。每个 Level 1 文本可包含多个子层级。对大量文本表现良好。 |
| OrganizationChart | `78` | 用于展示组织中的层级信息或汇报关系。该布局提供助理形状和组织图悬挂布局。 |
| PhasedProcess | `79` | 用于展示过程的三个阶段。限于三个 Level 1 项。前两个 Level 1 项各可包含四个 Level 2 项，第三个 Level 1 项可包含无限数量的 Level 2 项。最适合少量文本。 |
| PictureAccentBlocks | `80` | 用于从角落起始的块状图片组。对应文本垂直显示。非常适合作为标题或副标题幻灯片的点缀，或文档的章节分隔。 |
| PictureAccentList | `81` | 用于展示分组或相关信息。左上角的小形状设计用于容纳图片。强调 Level 2 文本而非 Level 1 文本，适合大量 Level 2 文本。 |
| PictureAccentProcess | `82` | 用于展示任务、流程或工作流中的顺序步骤。背景中的矩形形状设计用于容纳图片。 |
| PictureCaptionList | `83` | 用于展示非顺序或分组的信息块。顶部形状设计用于容纳图片，图片相对于文本更受强调。对带有简短文字说明的图片表现良好。 |
| PictureGrid | `84` | 用于在方形网格上展示图片。最适合少量的 Level 1 文本，该文本显示在图片上方。 |
| PictureLineup | `85` | 用于并排展示一系列图片。Level 1 文本覆盖图片顶部。Level 2 文本显示在图片下方。 |
| PictureStrips | `86` | 用于从上到下展示一系列图片，并在每张图片旁显示 Level 1 文本。 |
| PieProcess | `87` | 用于展示过程步骤，每个饼块最多增加到七个形状。Level 1 文本垂直显示。 |
| PlusandMinus | `88` | 用于展示两个想法的利弊。每个 Level 1 文本可包含多个子层级。对大量文本表现良好。限于两个 Level 1 项。 |
| ProcessArrows | `89` | 用于展示说明过程或工作流的信息。Level 1 文本显示在圆形中，Level 2 文本显示在箭头形状中。最适合最少文本并强调移动或方向。 |
| ProcessList | `90` | 用于展示任务、流程或工作流中的多个信息组或步骤及子步骤。Level 1 文本对应顶部水平形状，Level 2 文本对应每个相关顶部形状下方的垂直子步骤。 |
| PyramidList | `91` | 用于展示比例、相互关联或层级关系。文本显示在金字塔背景顶部的矩形形状中。 |
| RadialCluster | `92` | 用于展示与中心概念或主题相关的数据。顶部的 Level 1 文本显示在中心。Level 2 文本显示在周围形状中。可容纳最多七个 Level 2 形状。未使用的文本不显示，但在切换布局时仍可用。最适合少量文本。 |
| RadialCycle | `93` | 用于展示相对于中心概念的关系。强调中心圆以及外环圆形如何贡献于中心概念。第一行 Level 1 文本对应中心圆，其 Level 2 文本对应外环圆形。未使用的文本不显示，但在切换布局时仍可用。 |
| RadialList | `94` | 用于展示相对于中心概念的循环关系。中心形状可容纳图片。Level 1 文本显示在较小的圆形中，相关的 Level 2 文本显示在小圆形旁边。 |
| RadialVenn | `95` | 用于同时展示重叠关系和相对于中心概念的循环关系。第一行 Level 1 文本对应中心形状，Level 2 文本对应周围的圆形。未使用的文本不显示，但在切换布局时仍可用。 |
| RandomToResultProcess | `96` | 用于通过一系列步骤展示多个混乱想法如何汇聚为统一目标或想法。支持多个 Level 1 文本项，但首尾对应的形状固定。最适合少量 Level 1 文本和中等量的 Level 2 文本。 |
| RepeatingBendingProcess | `97` | 用于展示任务、流程或工作流中的进展或顺序步骤。最大化形状的水平和垂直显示空间。 |
| ReverseList | `98` | 用于在两项之间切换。仅显示前两项文本，每项可包含大量文本。非常适合展示两项之间的变化或顺序的转变。 |
| SegmentedCycle | `99` | 用于展示循环流中阶段、任务或事件的进展或序列。强调相互关联的部件。前七行 Level 1 文本对应楔形或饼形。未使用的文本不显示，但在切换布局时仍可用。 |
| SegmentedProcess | `100` | 用于展示任务、流程或工作流中的进展或顺序步骤。强调 Level 2 文本，因为每行显示在单独的形状中。 |
| SegmentedPyramid | `101` | 用于展示包含、比例或相互关联的关系。前九行 Level 1 文本出现在三角形形状中。未使用的文本不显示，但在切换布局时仍可用。最适合仅使用 Level 1 文本。 |
| SnapshotPictureList | `102` | 用于展示带有说明性文本的图片。Level 2 文本可显示信息列表。对大量文本表现良好。 |
| SpiralPicture | `103` | 用于展示最多五张图片及其对应的 Level 1 标题，这些图片呈螺旋状向中心排列。 |
| SquareAccentList | `104` | 用于将信息列表划分为类别。Level 2 文本出现在小方形旁边。对大量 Level 2 文本表现良好。 |
| StackedList | `105` | 用于展示任务、流程或工作流中的信息组或步骤。圆形包含 Level 1 文本，对应的矩形包含 Level 2 文本。对大量细节和极少的 Level 1 文本表现良好。 |
| StackedVenn | `106` | 用于展示重叠关系。是强调增长或渐变的良好选择。最适合仅使用 Level 1 文本。前七行 Level 1 文本对应一个圆形。未使用的文本不显示，但在切换布局时仍可用。 |
| StaggeredProcess | `107` | 用于展示向下的阶段进展。前五行 Level 1 文本各对应一个矩形。未使用的文本不显示，但在切换布局时仍可用。 |
| StepDownProcess | `108` | 用于展示包含多个步骤和子步骤的下降过程。最适合少量文本。 |
| StepUpProcess | `109` | 用于展示上升系列的步骤或信息列表。 |
| SubStepProcess | `110` | 用于展示每个 Level 1 文本之间有子步骤的多步骤过程。最适合少量文本，限于七个 Level 1 步骤。每个 Level 1 步骤可有无限子步骤。 |
| TableHierarchy | `111` | 用于展示从上到下构建的信息组及其层级。此布局不包含连接线。 |
| TableList | `112` | 用于展示等值的分组或相关信息。第一行 Level 1 文本对应顶部形状，其 Level 2 文本用于后续列表。 |
| TargetList | `113` | 用于展示相互关联或重叠的信息。前七行 Level 1 文本出现在矩形形状中。未使用的文本不显示，但在切换布局时仍可用。对 Level 1 和 Level 2 文本均表现良好。 |
| TextCycle | `114` | 用于表示循环流中阶段、任务或事件的连续序列。强调箭头或流而非阶段或步骤。最适合仅使用 Level 1 文本。 |
| TitlePictureLineup | `115` | 用于展示每张图片都有其标题和描述的一系列图片。Level 1 文本显示在图片上方的框中。Level 2 文本显示在图片下方。 |
| TitledMatrix | `116` | 用于展示四象限相对于整体的关系。第一行 Level 1 文本对应中心形状，前四行 Level 2 文本出现在象限中。未使用的文本不显示，但在切换布局时仍可用。 |
| TitledPictureAccentList | `117` | 用于展示每个 Level 2 文本配有点缀图片的信息列表。Level 1 文本显示在列表顶部的单独框中。 |
| TitledPictureBlocks | `118` | 用于展示一系列图片。Level 1 文本出现在每张图片上方。Level 2 文本出现在侧面并略微覆盖每张图片。 |
| TrapezoidList | `119` | 用于展示等值的分组或相关信息。对大量文本表现良好。 |
| UpwardArrow | `120` | 用于展示任务、流程或工作流中向上趋势的进展或步骤。前五行 Level 1 文本各对应箭头上的一点。最适合极少文本。未使用的文本不显示，但在切换布局时仍可用。 |
| VerticalAccentList | `121` | 用于展示信息列表。Level 2 文本出现在垂直箭头上的矩形形状中。强调 Level 2 文本而非 Level 1 文本，是中等量 Level 2 文本的良好选择。 |
| VerticalArrowList | `122` | 用于展示任务、流程或工作流中朝向共同目标的进展或顺序步骤。非常适合项目符号列表。 |
| VerticalBendingProcess | `123` | 用于展示任务、流程或工作流中的进展或顺序步骤。最大化形状的水平和垂直显示空间。比起方向或移动，更强调形状之间的相互关系。 |
| VerticalBlockList | `124` | 用于展示任务、流程或工作流中的信息组或步骤。对大量 Level 2 文本表现良好。是包含主点和多个子点的文本的良好选择。 |
| VerticalBoxList | `125` | 用于展示多个信息组，尤其是包含大量 Level 2 文本的组。是项目符号列表的良好选择。 |
| VerticalBulletList | `126` | 用于展示非顺序或分组的信息块。对标题较长或顶层信息的列表表现良好。 |
| VerticalChevronList | `127` | 用于展示任务、流程或工作流中的进展或顺序步骤，或强调移动或方向。强调 Level 2 文本而非 Level 1 文本，是大量 Level 2 文本的良好选择。 |
| VerticalCircleList | `128` | 用于展示顺序或分组的数据。最适合 Level 1 文本，显示在大圆形旁边。较低层级的文本用较小的圆形分隔。 |
| VerticalCurvedList | `129` | 用于展示曲线形的信息列表。要向强调圆形添加图片，请使用图片填充。 |
| VerticalEquation | `130` | 用于展示表示计划或结果的顺序步骤或任务。最后一行 Level 1 文本出现在箭头之后。最适合仅使用 Level 1 文本。 |
| VerticalPictureAccentList | `131` | 用于展示非顺序或分组的信息块。小圆形设计用于容纳图片。 |
| VerticalPictureList | `132` | 用于展示非顺序或分组的信息块。左侧的小形状设计用于容纳图片。 |
| VerticalProcess | `133` | 用于从上到下展示任务、流程或工作流的进展或顺序步骤。由于垂直空间受限，最适合使用 Level 1 文本。 |
| Custom | `134` | 表示具有自定义布局模板的 SmartArt 图表 |
| PictureOrganizationChart | `135` | 用于展示组织中的层级信息或汇报关系，并配有相应图片。该布局提供助理形状和组织图悬挂布局。 |

### 另见

* 命名空间 [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->