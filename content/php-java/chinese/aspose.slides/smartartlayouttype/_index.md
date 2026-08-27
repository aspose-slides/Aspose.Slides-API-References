---
title: SmartArtLayoutType
second_title: Aspose.Sildes PHP 通过 Java API 参考
description: 
type: docs

url: /zh/aspose.slides/smartartlayouttype/
---
## SmartArtLayoutType 类

表示 SmartArt 图表的布局类型。

## 常量

| 名称 | 值 | 描述 |
| --- | --- | --- |
[AccentProcess](#AccentProcess) | 0 | 用于显示任务、流程或工作流中的进展、时间线或顺序步骤。非常适合展示 Level 1 和 Level 2 文本。 |
[AccentedPicture](#AccentedPicture) | 1 | 用于显示中心的照片构想，并在侧面展示相关想法。顶部的 Level 1 文本显示在中心图片上方。其他 Level 1 形状对应的文本显示在小圆形图片旁边。此布局在没有文本时也能很好使用。 |
[AlternatingFlow](#AlternatingFlow) | 2 | 用于显示任务、流程或工作流中的信息组或顺序步骤。强调信息组之间的交互或关系。 |
[AlternatingHexagons](#AlternatingHexagons) | 3 | 用于表示一系列相互关联的想法。Level 1 文本显示在六边形内部。Level 2 文本显示在形状外部。 |
[AlternatingPictureBlocks](#AlternatingPictureBlocks) | 4 | 用于从上至下显示一系列图片。文本交替出现在图片的右侧或左侧。 |
[AlternatingPictureCircles](#AlternatingPictureCircles) | 5 | 用于显示一组带文本的图片。对应的文本出现在中心圆形内，图像从左到右交替排列。 |
[ArrowRibbon](#ArrowRibbon) | 6 | 用于显示相关或对立的概念及其某种关联，例如相反的力量。前两行 Level 1 文本用于箭头中的文字。未使用的文本不会显示，但在切换布局时仍可用。 |
[AscendingPictureAccentProcess](#AscendingPictureAccentProcess) | 7 | 用于显示一系列向上排列的图片及说明文本。最适合少量文本。 |
[Balance](#Balance) | 8 | 用于比较或展示两个想法之间的关系。前两行 Level 1 文本分别对应中心点两侧顶部的文本。强调 Level 2 文本，每侧最多限于四个形状。包含 Level 2 文本的形状数量较多的一侧会占优势。未使用的文本不会显示，但切换布局时仍可用。 |
[BasicBendingProcess](#BasicBendingProcess) | 9 | 用于显示任务、流程或工作流中的进展或顺序步骤。最大化形状的水平和垂直显示空间。 |
[BasicBlockList](#BasicBlockList) | 10 | 用于显示非顺序或分组的信息块。最大化形状的水平和垂直显示空间。 |
[BasicChevronProcess](#BasicChevronProcess) | 11 | 用于显示进展、时间线、任务、流程或工作流的顺序步骤，或突出移动或方向。Level 1 文本显示在箭头形状内部，Level 2 文本显示在箭头形状下方。 |
[BasicCycle](#BasicCycle) | 12 | 用于表示在循环流中持续的阶段、任务或事件序列。强调阶段或步骤，而非连接的箭头或流程。仅使用 Level 1 文本时效果最佳。 |
[BasicMatrix](#BasicMatrix) | 13 | 用于在四象限中显示组件与整体的关系。前四行 Level 1 文本出现在四象限中。未使用的文本不会显示，但在切换布局时仍可用。 |
[BasicPie](#BasicPie) | 14 | 用于展示各个部分如何构成整体。前七行 Level 1 文本对应均匀分布的楔形或饼形。顶部的 Level 1 文本形状位于饼形之外以示强调。未使用的文本不会显示，但切换布局时仍可用。 |
[BasicProcess](#BasicProcess) | 15 | 用于显示任务、流程或工作流中的进展或顺序步骤。 |
[BasicPyramid](#BasicPyramid) | 16 | 用于显示比例、相互关联或层级关系，最大组件位于底部并向上收窄。Level 1 文本出现在金字塔的各段，Level 2 文本出现在每段旁边的形状中。 |
[BasicRadial](#BasicRadial) | 17 | 用于在循环中显示与中心思想的关系。第一行 Level 1 文本对应中心形状，其 Level 2 文本对应周围的圆形形状。未使用的文本不会显示，但在切换布局时仍可用。 |
[BasicTarget](#BasicTarget) | 18 | 用于展示包含、渐变或层级关系。前五行 Level 1 文本与一个圆形关联。未使用的文本不会显示，但切换布局时仍可用。 |
[BasicTimeline](#BasicTimeline) | 19 | 用于显示任务、流程或工作流的顺序步骤，或展示时间线信息。对 Level 1 和 Level 2 文本均有良好展示效果。 |
[BasicVenn](#BasicVenn) | 20 | 用于显示重叠或相互关联的关系。前七行 Level 1 文本对应一个圆形。如果 Level 1 文本不超过四行，文本位于圆形内部；超过四行时，文本位于圆形外部。未使用的文本不会显示，但在切换布局时仍可用。 |
[BendingPictureAccentList](#BendingPictureAccentList) | 21 | 用于显示非顺序或分组的信息块。小圆形形状用于容纳图片。对 Level 1 和 Level 2 文本都有良好展示效果。最大化形状的水平和垂直显示空间。 |
[BendingPictureBlocks](#BendingPictureBlocks) | 22 | 用于显示一系列图片。覆盖底部角落的框可容纳少量文本。 |
[BendingPictureCaption](#BendingPictureCaption) | 23 | 用于显示顺序排列的图片系列。覆盖底部角落的框可容纳少量文本。 |
[BendingPictureCaptionList](#BendingPictureCaptionList) | 24 | 用于显示一系列图片。标题和描述出现在每张图片下方的注释形状中。 |
[BendingPictureSemiTransparentText](#BendingPictureSemiTransparentText) | 25 | 用于显示一系列图片。半透明框覆盖图片的下部，包含所有层级的文本。 |
[BlockCycle](#BlockCycle) | 26 | 用于表示在循环流中持续的阶段、任务或事件序列。强调阶段或步骤，而非连接的箭头或流程。 |
[BubblePictureList](#BubblePictureList) | 27 | 用于显示一系列图片。可容纳最多八张 Level 1 图片。未使用的文本和图片不会显示，但切换布局时仍可用。对少量文本效果最佳。 |
[CaptionedPictures](#CaptionedPictures) | 28 | 用于显示带有多层文本的图片。对少量 Level 1 文本和中等量 Level 2 文本效果最佳。 |
[ChevronList](#ChevronList) | 29 | 用于展示构成整体工作流的多个过程的进展。也适用于说明对立的过程。Level 1 文本对应左侧的第一个箭头形状，Level 2 文本对应每个包含 Level 1 文本的形状的水平子步骤。 |
[CircleAccentTimeline](#CircleAccentTimeline) | 30 | 用于显示一系列事件或时间线信息。Level 1 文本出现在较大圆形旁边，Level 2 文本出现在较小圆形旁边。 |
[CircleArrowProcess](#CircleArrowProcess) | 31 | 用于显示带有每项支持文本的顺序项目。此图在少量 Level 1 文本时效果最佳。 |
[CirclePictureHierarchy](#CirclePictureHierarchy) | 32 | 用于显示组织中的层级信息或汇报关系。图片显示在圆形中，对应的文本出现在图片旁边。 |
[CircleRelationship](#CircleRelationship) | 33 | 用于显示与中心思想的关系（向中心或从中心）。Level 2 文本非顺序添加，限于五项。只能有一个 Level 1 项。 |
[CircularBendingProcess](#CircularBendingProcess) | 34 | 用于显示任务、流程或工作流中较长或非线性的序列或步骤。仅使用 Level 1 文本时效果最佳。最大化形状的水平和垂直显示空间。 |
[CircularPictureCallout](#CircularPictureCallout) | 35 | 用于显示中心思想及子想法或相关项目。第一张图片的文本覆盖图片的下部。其他 Level 1 形状的对应文本出现在小圆形图片旁边。此图在没有文本时也能很好使用。 |
[ClosedChevronProcess](#ClosedChevronProcess) | 36 | 用于显示进展、时间线或任务、流程、工作流的顺序步骤，或突出移动或方向。可用于强调起始形状中的信息。仅使用 Level 1 文本时效果最佳。 |
[ContinuousArrowProcess](#ContinuousArrowProcess) | 37 | 用于显示任务、流程或工作流的时间线或顺序步骤。由于每行 Level 1 文本出现在箭头形状内部，使用 Level 1 文本时效果最佳。Level 2 文本出现在箭头形状外部。 |
[ContinuousBlockProcess](#ContinuousBlockProcess) | 38 | 用于显示任务、流程或工作流的进展或顺序步骤。对最少量的 Level 1 和 Level 2 文本效果最佳。 |
[ContinuousCycle](#ContinuousCycle) | 39 | 用于表示在循环流中持续的阶段、任务或事件序列。强调所有组件之间的连接。仅使用 Level 1 文本时效果最佳。 |
[ContinuousPictureList](#ContinuousPictureList) | 40 | 用于显示相互关联的信息组。圆形形状旨在容纳图片。 |
[ConvergingArrows](#ConvergingArrows) | 41 | 用于显示汇聚到中心点的想法或概念。仅使用 Level 1 文本时效果最佳。 |
[ConvergingRadial](#ConvergingRadial) | 42 | 用于在循环中显示概念或组件与中心思想的关系。第一行 Level 1 文本对应中心圆形，Level 2 文本对应周围的矩形形状。未使用的文本不会显示，但在切换布局时仍可用。 |
[CounterbalanceArrows](#CounterbalanceArrows) | 43 | 用于显示两个对立的想法或概念。前两行 Level 1 文本分别对应一个箭头，并能很好地配合 Level 2 文本。未使用的文本不会显示，但切换布局时仍可用。 |
[CycleMatrix](#CycleMatrix) | 44 | 用于在循环进展中显示与中心思想的关系。前四行 Level 1 文本对应楔形或饼形，Level 2 文本出现在楔形或饼形旁边的矩形中。未使用的文本不会显示，但在切换布局时仍可用。 |
[DescendingBlockList](#DescendingBlockList) | 45 | 用于显示相关想法或信息列表的分组。文本形状高度依次递减，Level 1 文本垂直显示。 |
[DescendingProcess](#DescendingProcess) | 46 | 用于显示递降的事件序列。第一行 Level 1 文本位于箭头顶部，最后一行 Level 1 文本位于箭头底部。仅显示前七个 Level 1 项。对少量至中等量的文本效果最佳。 |
[DetailedProcess](#DetailedProcess) | 47 | 使用大量 Level 2 文本来显示阶段性的进展。 |
[DivergingArrows](#DivergingArrows) | 48 | 用于显示从中心来源向外扩展的想法或概念。仅使用 Level 1 文本时效果最佳。 |
[DivergingRadial](#DivergingRadial) | 49 | 用于在循环中显示与中心思想的关系。第一行 Level 1 文本对应中心圆形。强调周围的圆形而非中心思想。未使用的文本不会显示，但在切换布局时仍可用。 |
[Equation](#Equation) | 50 | 用于显示描绘计划或结果的顺序步骤或任务。最后一行 Level 1 文本出现在等号 (=) 后。仅使用 Level 1 文本时效果最佳。 |
[FramedTextPicture](#FramedTextPicture) | 51 | 用于显示带有对应 Level 1 文本并以框架显示的图片。 |
[Funnel](#Funnel) | 52 | 用于显示信息过滤或各部分合并为整体的过程。强调最终结果。可容纳最多四行 Level 1 文本；其中最后一行显示在漏斗下方，其他行对应圆形。未使用的文本不会显示，但在切换布局时仍可用。 |
[Gear](#Gear) | 53 | 用于显示互锁的想法。前三行 Level 1 文本对应齿轮形状，其对应的 Level 2 文本出现在齿轮旁的矩形中。未使用的文本不会显示，但切换布局时仍可用。 |
[GridMatrix](#GridMatrix) | 54 | 用于显示概念在两个轴上的布局。强调各个组件而非整体。前四行 Level 1 文本出现在四象限中。未使用的文本不会显示，但在切换布局时仍可用。 |
[GroupedList](#GroupedList) | 55 | 用于显示信息的组及子组，或任务、流程、工作流中的步骤和子步骤。第 1 级文本对应顶层水平形状，第 2 级文本对应每个相关顶层形状下的垂直子步骤。非常适合强调子组或子步骤、层级信息或多个信息列表。 |
[HalfCircleOrganizationChart](#HalfCircleOrganizationChart) | 56 | 用于展示组织中的层级信息或汇报关系。此布局提供助理形状和组织结构图悬挂布局。 |
[HexagonCluster](#HexagonCluster) | 57 | 用于显示带有说明性文字的图片。小六角形表示图片与文字的配对。最适合少量文字。 |
[Hierarchy](#Hierarchy) | 58 | 用于展示从上到下的层级关系。 |
[HierarchyList](#HierarchyList) | 59 | 用于展示跨组的层级关系。也可用于分组或列出信息。 |
[HorizontalBulletList](#HorizontalBulletList) | 60 | 用于展示非顺序或分组的信息列表。适用于大量文字。所有文字具有相同的强调程度，且不暗示方向。 |
[HorizontalHierarchy](#HorizontalHierarchy) | 61 | 用于横向展示层级关系。非常适合决策树。 |
[HorizontalLabeledHierarchy](#HorizontalLabeledHierarchy) | 62 | 用于横向且层级分组的层级关系展示。强调标题或第 1 级文本。第 1 级文本的第一行显示在层级起始的形状中，其余第 1 级文本行显示在高矩形的顶部。 |
[HorizontalMultiLevelHierarchy](#HorizontalMultiLevelHierarchy) | 63 | 用于横向展示大量层级信息。层级顶部以垂直方式显示。此布局支持层级中的多个层级。 |
[HorizontalOrganizationChart](#HorizontalOrganizationChart) | 64 | 用于横向展示层级信息或组织中的汇报关系。此布局提供助理形状和组织结构图悬挂布局。 |
[HorizontalPictureList](#HorizontalPictureList) | 65 | 用于展示非顺序或分组信息，并强调相关图片。顶部形状专为容纳图片而设计。 |
[IncreasingArrowsProcess](#IncreasingArrowsProcess) | 66 | 用于显示过程中的顺序且重叠的步骤。仅限五个第 1 级项目。第 2 级可包含大量文字。 |
[IncreasingCircleProcess](#IncreasingCircleProcess) | 67 | 用于展示一系列步骤，圆形内部随每一步增长。限制为七个第 1 级步骤，但第 2 级项目不受限制。适合大量第 2 级文字。 |
[InvertedPyramid](#InvertedPyramid) | 68 | 用于展示比例、相互关联或层级关系，最大部件位于顶部并逐渐收窄。第 1 级文本显示在金字塔段中，第 2 级文本显示在每段旁边的形状中。 |
[LabeledHierarchy](#LabeledHierarchy) | 69 | 用于从上到下且分层分组的层级关系展示。强调标题或第 1 级文本。第 1 级文本的第一行显示在层级起始的形状中，随后所有第 1 级文本行显示在长矩形的左侧。 |
[LinearVenn](#LinearVenn) | 70 | 用于在序列中展示重叠关系。仅使用第 1 级文本时效果最佳。 |
[LinedList](#LinedList) | 71 | 用于将大量文字分为类别和子类别展示。适合多层级文字。相同层级的文字以线条分隔。 |
[MultidirectionalCycle](#MultidirectionalCycle) | 72 | 用于表示可以向任意方向延展的连续阶段、任务或事件序列。 |
[NameandTitleOrganizationChart](#NameandTitleOrganizationChart) | 73 | 用于展示组织中的层级信息或汇报关系。要在标题框中输入文字，请直接在较小的矩形形状中键入。此布局提供助理形状和组织结构图悬挂布局。 |
[NestedTarget](#NestedTarget) | 74 | 用于展示包含关系。第 1 级文本的前三行对应形状左上方的文字，第 2 级文本对应较小的形状。最适合少量第 2 级文字。未使用的文字不显示，但在切换布局时仍可用。 |
[NondirectionalCycle](#NondirectionalCycle) | 75 | 用于在循环流中表示连续的阶段、任务或事件序列。每个形状的重要性相同。适用于不需指示方向的情况。 |
[OpposingArrows](#OpposingArrows) | 76 | 用于展示两种相对的想法，或从中心点分散的想法。第 1 级文本的前两行对应各自的箭头。未使用的文字不显示，但在切换布局时仍可用。 |
[OpposingIdeas](#OpposingIdeas) | 77 | 用于展示两种相对或对比的想法。可包含一或两个第 1 级项目。每个第 1 级文字可包含多个子层级。适合大量文字。 |
[OrganizationChart](#OrganizationChart) | 78 | 用于展示组织中的层级信息或汇报关系。此布局提供助理形状和组织结构图悬挂布局。 |
[PhasedProcess](#PhasedProcess) | 79 | 用于展示过程的三个阶段。仅限三个第 1 级项目。前两个第 1 级项目各可包含四个第 2 级项目，第三个第 1 级项目可包含无限数量的第 2 级项目。最适合少量文字。 |
[PictureAccentBlocks](#PictureAccentBlocks) | 80 | 用于从角落起以块状方式显示一组图片。对应文字垂直显示。适合作为标题或副标题幻灯片的强调，或文档章节分隔。 |
[PictureAccentList](#PictureAccentList) | 81 | 用于展示分组或相关信息。上角的小形状用于容纳图片。强调第 2 级文字而非第 1 级文字，适合大量第 2 级文字。 |
[PictureAccentProcess](#PictureAccentProcess) | 82 | 用于显示任务、流程或工作流中的顺序步骤。背景中的矩形形状用于容纳图片。 |
[PictureCaptionList](#PictureCaptionList) | 83 | 用于展示非顺序或分组的信息块。顶部形状用于容纳图片，且图片相对于文字更受强调。适合带有简短文字说明的图片。 |
[PictureGrid](#PictureGrid) | 84 | 用于在方形网格上布局图片。最佳搭配少量第 1 级文字，文字显示在图片上方。 |
[PictureLineup](#PictureLineup) | 85 | 用于并排显示一系列图片。第 1 级文字位于图片顶部。第 2 级文字显示在图片下方。 |
[PictureStrips](#PictureStrips) | 86 | 用于从上到下展示一系列图片，每张图片旁边配有第 1 级文字。 |
[PieProcess](#PieProcess) | 87 | 用于展示过程步骤，每个饼块大小递增，最多七个形状。第 1 级文字垂直显示。 |
[PlusandMinus](#PlusandMinus) | 88 | 用于展示两个想法的优缺点。每个第 1 级文字可包含多个子层级。适合大量文字。限制为两个第 1 级项目。 |
[ProcessArrows](#ProcessArrows) | 89 | 用于展示说明过程或工作流的信息。第 1 级文字位于圆形形状中，第 2 级文字位于箭头形状中。最适合文字少且强调移动或方向的场景。 |
[ProcessList](#ProcessList) | 90 | 用于展示任务、流程或工作流中的多个信息组或步骤及子步骤。第 1 级文字对应顶部水平形状，第 2 级文字对应每个相关顶层形状下的垂直子步骤。 |
[PyramidList](#PyramidList) | 91 | 用于展示比例、相互关联或层级关系。文字显示在金字塔背景顶部的矩形形状中。 |
[RadialCluster](#RadialCluster) | 92 | 用于展示与中心概念或主题相关的数据。顶部的第 1 级文字位于中心，第 2 级文字位于周围形状中。可容纳最多七个第 2 级形状。未使用的文字不显示，但在切换布局时仍可用。最适合少量文字。 |
[RadialCycle](#RadialCycle) | 93 | 用于展示与中心概念的关联。突出中心圆圈中的信息以及外环圆圈信息对中心概念的贡献。第 1 级文字的第一行对应中心圆圈，其第 2 级文字对应外环圆圈。未使用的文字不显示，但在切换布局时仍可用。 |
[RadialList](#RadialList) | 94 | 用于在循环中展示与中心概念的关系。中心形状可容纳图片。第 1 级文字显示在较小的圆圈中，相关的第 2 级文字显示在小圆圈旁边。 |
[RadialVenn](#RadialVenn) | 95 | 用于在循环中同时展示重叠关系和与中心概念的关联。第 1 级文字的第一行对应中心形状，第 2 级文字的各行对应周围的圆形形状。未使用的文字不显示，但在切换布局时仍可用。 |
[RandomToResultProcess](#RandomToResultProcess) | 96 | 通过一系列步骤展示多个混乱想法如何汇聚成统一目标或理念。支持多个第 1 级文字项目，但第一和最后的第 1 级对应形状是固定的。最适合少量第 1 级文字和中等量第 2 级文字。 |
[RepeatingBendingProcess](#RepeatingBendingProcess) | 97 | 用于展示任务、流程或工作流中的进程或顺序步骤。最大化形状的横向和纵向显示空间。 |
[ReverseList](#ReverseList) | 98 | 用于在两项之间切换。仅显示前两项文字，每项可包含大量文字。适合展示两项之间的变化或顺序的转变。 |
[SegmentedCycle](#SegmentedCycle) | 99 | 用于在循环流中展示进程或阶段、任务、事件的序列。强调相互关联的部分。第 1 级文字的前七行分别对应一个楔形或饼形。未使用的文字不显示，但在切换布局时仍可用。 |
[SegmentedProcess](#SegmentedProcess) | 100 | 用于展示任务、流程或工作流中的进程或顺序步骤。强调第 2 级文字，因为每行文字出现在单独的形状中。 |
[SegmentedPyramid](#SegmentedPyramid) | 101 | 用于展示包含、比例或相互关联的关系。第 1 级文字的前九行出现在三角形形状中。未使用的文字不显示，但在切换布局时仍可用。最适合仅使用第 1 级文字。 |
[SnapshotPictureList](#SnapshotPictureList) | 102 | 用于显示带说明文字的图片。第 2 级文字可展示信息列表。适合大量文字。 |
[SpiralPicture](#SpiralPicture) | 103 | 用于展示最多五张图片的系列，配以对应的第 1 级标题，螺旋式汇聚至中心。 |
[SquareAccentList](#SquareAccentList) | 104 | 用于展示按类别划分的信息列表。第 2 级文字出现在小方形旁边。适合大量第 2 级文字。 |
[StackedList](#StackedList) | 105 | 用于展示任务、流程或工作流中的信息组或步骤。圆形形状包含第 1 级文字，对应的矩形包含第 2 级文字。适合细节繁多且第 1 级文字较少的情况。 |
[StackedVenn](#StackedVenn) | 106 | 用于展示重叠关系。是强调成长或层次的良好选择。最适合仅使用第 1 级文字。第 1 级文字的前七行对应一个圆形。未使用的文字不显示，但在切换布局时仍可用。 |
[StaggeredProcess](#StaggeredProcess) | 107 | 用于展示阶段性的向下进程。第 1 级文字的前五行对应矩形。未使用的文字不显示，但在切换布局时仍可用。 |
[StepDownProcess](#StepDownProcess) | 108 | 用于展示多步骤及子步骤的下降过程。最适合少量文字。 |
[StepUpProcess](#StepUpProcess) | 109 | 用于展示上升的步骤系列或信息列表。 |
[SubStepProcess](#SubStepProcess) | 110 | 用于展示多步骤过程，每个第 1 级文字之间包含子步骤。最适合少量文字，且限制为七个第 1 级步骤。每个第 1 级步骤可有无限子步骤。 |
[TableHierarchy](#TableHierarchy) | 111 | 用于展示从上到下构建的信息组及每组内部的层级。此布局不包含连接线。 |
[TableList](#TableList) | 112 | 用于显示价值相等的分组或相关信息。第一行第 1 级文本对应顶部形状，其第 2 级文本用于后续列表。 |
[TargetList](#TargetList) | 113 | 用于显示相互关联或重叠的信息。前七行第 1 级文本分别显示在矩形形状中。未使用的文本不会显示，但在切换布局时仍可用。适用于第 1 级和第 2 级文本。 |
[TextCycle](#TextCycle) | 114 | 用于在循环流程中表示持续的阶段、任务或事件序列。强调箭头或流向，而非各阶段或步骤。仅适用于第 1 级文本。 |
[TitlePictureLineup](#TitlePictureLineup) | 115 | 用于显示一系列各自拥有标题和描述的图片。第 1 级文本显示在图片上方的框中。第 2 级文本显示在图片下方。 |
[TitledMatrix](#TitledMatrix) | 116 | 用于显示四个象限相对于整体的关系。第一行第 1 级文本对应中心形状，前四行第 2 级文本出现在各象限中。未使用的文本不会显示，但在切换布局时仍可用。 |
[TitledPictureAccentList](#TitledPictureAccentList) | 117 | 用于显示信息列表，并为每个第 2 级文本配以强调图片。第 1 级文本显示在列表顶部的独立框中。 |
[TitledPictureBlocks](#TitledPictureBlocks) | 118 | 用于显示一系列图片。第 1 级文本显示在每张图片上方。第 2 级文本显示在侧面并略微重叠每张图片。 |
[TrapezoidList](#TrapezoidList) | 119 | 用于显示价值相等的分组或相关信息。适用于大量文本。 |
[UpwardArrow](#UpwardArrow) | 120 | 用于显示任务、流程或工作流中向上趋势的进展或步骤。前五行第 1 级文本分别对应箭头上的一个点。最适合少量文本。未使用的文本不会显示，但在切换布局时仍可用。 |
[VerticalAccentList](#VerticalAccentList) | 121 | 用于显示信息列表。第 2 级文本出现在垂直箭头形状上的矩形中。强调第 2 级文本而非第 1 级文本，适合中等量的第 2 级文本。 |
[VerticalArrowList](#VerticalArrowList) | 122 | 用于显示任务、流程或工作流中朝向共同目标的进展或顺序步骤。适用于项目符号信息列表。 |
[VerticalBendingProcess](#VerticalBendingProcess) | 123 | 用于显示任务、流程或工作流的进展或顺序步骤。最大化形状的水平和垂直显示空间。更强调形状之间的相互关系，而非方向或移动。 |
[VerticalBlockList](#VerticalBlockList) | 124 | 用于显示任务、流程或工作流中的信息组或步骤。适用于大量第 2 级文本。是主旨与多个子要点文本的良好选择。 |
[VerticalBoxList](#VerticalBoxList) | 125 | 用于显示多个信息组，特别是包含大量第 2 级文本的组。是项目符号信息列表的良好选择。 |
[VerticalBulletList](#VerticalBulletList) | 126 | 用于显示非顺序或分组的信息块。适用于标题较长或顶层信息的列表。 |
[VerticalChevronList](#VerticalChevronList) | 127 | 用于显示任务、流程或工作流的进展或顺序步骤，或强调移动或方向。强调第 2 级文本而非第 1 级文本，是大量第 2 级文本的良好选择。 |
[VerticalCircleList](#VerticalCircleList) | 128 | 用于显示顺序或分组的数据。最适合第 1 级文本，显示在大圆形旁侧。较低级别的文本用更小的圆形分隔。 |
[VerticalCurvedList](#VerticalCurvedList) | 129 | 用于显示弧形信息列表。若要向强调圆形添加图片，请使用图片填充。 |
[VerticalEquation](#VerticalEquation) | 130 | 用于显示描绘计划或结果的顺序步骤或任务。最后一行第 1 级文本出现在箭头之后。仅适用于第 1 级文本。 |
[VerticalPictureAccentList](#VerticalPictureAccentList) | 131 | 用于显示非顺序或分组的信息块。小圆形设计用于容纳图片。 |
[VerticalPictureList](#VerticalPictureList) | 132 | 用于显示非顺序或分组的信息块。左侧的小形状设计用于容纳图片。 |
[VerticalProcess](#VerticalProcess) | 133 | 用于从上到下显示任务、流程或工作流的进展或顺序步骤。由于垂直空间受限，最适合第 1 级文本。 |
[Custom](#Custom) | 134 | 表示具有自定义布局模板的 SmartArt 图表 |
[PictureOrganizationChart](#PictureOrganizationChart) | 135 | 用于显示组织中的层级信息或汇报关系，并配有相应的图片。此布局提供助理形状和组织结构图悬挂布局。 |

---

### AccentProcess {#AccentProcess}
用于显示任务、流程或工作流的进展、时间线或顺序步骤。适用于展示第 1 级和第 2 级文本。

---

### AccentedPicture {#AccentedPicture}
用于展示中心的摄影构思及其侧面的相关想法。顶部第 1 级文本显示在中心图片上方。其他第 1 级形状对应的文本显示在小圆形图片旁侧。此布局在没有文本时也能良好工作。

---

### AlternatingFlow {#AlternatingFlow}
用于显示任务、流程或工作流中的信息组或顺序步骤。强调信息组之间的交互或关系。

---

### AlternatingHexagons {#AlternatingHexagons}
用于表示一系列相互关联的想法。第 1 级文本显示在六边形内部。第 2 级文本显示在形状外部。

---

### AlternatingPictureBlocks {#AlternatingPictureBlocks}
用于从上到下显示一系列图片。文本交替显示在图片的右侧或左侧。

---

### AlternatingPictureCircles {#AlternatingPictureCircles}
用于显示带有文本的一组图片。相应的文本显示在中心圆圈中，图像从左到右交替排列。

---

### ArrowRibbon {#ArrowRibbon}
用于展示具有某种关联的相关或对立概念，例如相反的力量。前两行第 1 级文本用于箭头中的文字。未使用的文本不会显示，但在切换布局时仍可用。

---

### AscendingPictureAccentProcess {#AscendingPictureAccentProcess}
用于展示一系列递增的图片并配以描述性文本。最适合少量文本。

---

### Balance {#Balance}
用于比较或展示两个想法之间的关系。前两行第 1 级文本对应中心点两侧顶部的文字。强调第 2 级文本，每侧最多四个形状可容纳第 2 级文本。平衡会倾向于包含更多第 2 级文本形状的一侧。未使用的文本不会显示，但在切换布局时仍可用。

---

### BasicBendingProcess {#BasicBendingProcess}
用于显示任务、流程或工作流的进展或顺序步骤。最大化形状的水平和垂直显示空间。

---

### BasicBlockList {#BasicBlockList}
用于显示非顺序或分组的信息块。最大化形状的水平和垂直显示空间。

---

### BasicChevronProcess {#BasicChevronProcess}
用于显示进展、时间线、任务、流程或工作流的顺序步骤，或强调移动或方向。第 1 级文本显示在箭头形状内部，而第 2 级文本显示在箭头形状下方。

---

### BasicCycle {#BasicCycle}
用于在循环流程中表示持续的阶段、任务或事件序列。强调阶段或步骤，而非连接的箭头或流向。仅适用于第 1 级文本。

---

### BasicMatrix {#BasicMatrix}
用于在象限中显示组件与整体的关系。前四行第 1 级文本出现在各象限中。未使用的文本不会显示，但在切换布局时仍可用。

---

### BasicPie {#BasicPie}
用于展示各部分如何组成整体。前七行第 1 级文本对应均匀分布的楔形或饼形。顶部第 1 级文本形状位于其余饼形之外以示强调。未使用的文本不会显示，但在切换布局时仍可用。

---

### BasicProcess {#BasicProcess}
用于显示任务、流程或工作流的进展或顺序步骤。

---

### BasicPyramid {#BasicPyramid}
用于显示比例、相互关联或层级关系，最大组件位于底部，向上逐渐缩小。第 1 级文本显示在金字塔的各段中，第 2 级文本显示在每段旁边的形状中。

---

### BasicRadial {#BasicRadial}
用于在循环中显示与中心思想的关系。第一行第 1 级文本对应中心形状，其第 2 级文本对应周围的圆形形状。未使用的文本不会显示，但在切换布局时仍可用。

---

### BasicTarget {#BasicTarget}
用于展示包含、层次或层级关系。前五行第 1 级文本与一个圆形关联。未使用的文本不会显示，但在切换布局时仍可用。

---

### BasicTimeline {#BasicTimeline}
用于显示任务、流程或工作流的顺序步骤，或展示时间线信息。适用于第 1 级和第 2 级文本。

---

### BasicVenn {#BasicVenn}
用于展示重叠或相互关联的关系。前七行第 1 级文本对应一个圆形。如果第 1 级文本行数不超过四行，文本位于圆形内部；超过四行时，文本位于圆形外部。未使用的文本不会显示，但在切换布局时仍可用。

---

### BendingPictureAccentList {#BendingPictureAccentList}
用于显示非顺序或分组的信息块。小圆形设计用于容纳图片。适用于展示第 1 级和第 2 级文本。最大化形状的水平和垂直显示空间。

---

### BendingPictureBlocks {#BendingPictureBlocks}
用于显示一系列图片。覆盖底角的框可容纳少量文本。

---

### BendingPictureCaption {#BendingPictureCaption}
用于显示顺序排列的一系列图片。覆盖底角的框可容纳少量文本。

---

### BendingPictureCaptionList {#BendingPictureCaptionList}
用于显示一系列图片。标题和描述出现在每张图片下方的标注形状中。

---

### BendingPictureSemiTransparentText {#BendingPictureSemiTransparentText}
用于显示一系列图片。半透明框覆盖图片下部并容纳所有级别的文本。

---

### BlockCycle {#BlockCycle}
用于在循环流程中表示持续的阶段、任务或事件序列。强调阶段或步骤，而非连接的箭头或流向。

---

### BubblePictureList {#BubblePictureList}
用于显示一系列图片。可容纳最多八个第 1 级图片。未使用的文本和图片不会显示，但在切换布局时仍可用。最适合少量文本。

---

### CaptionedPictures {#CaptionedPictures}
用于显示带有多级文本的图片。最适合少量第 1 级文本和中等量第 2 级文本。

---

### ChevronList {#ChevronList}
用于展示构成整体工作流的多个过程的进展。也适用于说明对比过程。第 1 级文本对应左侧的第一个箭头形状，而第 2 级文本对应每个包含第 1 级文本的形状的水平子步骤。

---

### CircleAccentTimeline {#CircleAccentTimeline}
用于显示一系列事件或时间线信息。第 1 级文本出现在较大圆形旁侧，第 2 级文本出现在较小圆形旁侧。

---

### CircleArrowProcess {#CircleArrowProcess}
Use to show sequential items with supporting text for each item. This diagram works best with small amounts of Level 1 text.

---

### CirclePictureHierarchy {#CirclePictureHierarchy}
用于以圆形显示层级信息或组织中的汇报关系。图片显示为圆形，相应的文本出现在图片旁边。

---

### CircleRelationship {#CircleRelationship}
用于展示与中心思想的关系。Level 2 文本以非顺序方式添加，且最多五项。只能有一个 Level 1 项目。

---

### CircularBendingProcess {#CircularBendingProcess}
用于显示任务、过程或工作流中的长或非线性序列或步骤。仅使用 Level 1 文本时效果最佳。最大化形状的水平和垂直显示空间。

---

### CircularPictureCallout {#CircularPictureCallout}
用于显示中心思想及其子思想或相关项。第一张图片的文本覆盖图片的下部。其他 Level 1 形状的对应文本出现在小圆形图片旁边。该图表在无文本时也能良好工作。

---

### ClosedChevronProcess {#ClosedChevronProcess}
用于展示任务、过程或工作流中的进展、时间线或顺序步骤，或强调移动或方向。可用于强调起始形状中的信息。仅使用 Level 1 文本时效果最佳。

---

### ContinuousArrowProcess {#ContinuousArrowProcess}
用于展示任务、过程或工作流中的时间线或顺序步骤。由于每行 Level 1 文本显示在箭头形状内，最佳使用 Level 1 文本。Level 2 文本显示在箭头形状外。

---

### ContinuousBlockProcess {#ContinuousBlockProcess}
用于展示任务、过程或工作流中的进展或顺序步骤。最适合使用最少的 Level 1 和 Level 2 文本。

---

### ContinuousCycle {#ContinuousCycle}
用于表示循环流程中持续的阶段、任务或事件序列。强调所有组件之间的连接。仅使用 Level 1 文本时效果最佳。

---

### ContinuousPictureList {#ContinuousPictureList}
用于显示相互关联信息的组。圆形形状设计用于容纳图片。

---

### ConvergingArrows {#ConvergingArrows}
用于展示收敛到中心点的想法或概念。仅使用 Level 1 文本时效果最佳。

---

### ConvergingRadial {#ConvergingRadial}
用于显示概念或组件与中心思想的循环关系。第一行 Level 1 文本对应中心圆形，Level 2 文本对应周围的矩形形状。未使用的文本不显示，但在切换布局时仍可用。

---

### CounterbalanceArrows {#CounterbalanceArrows}
用于展示两个相对的想法或概念。前两行 Level 1 文本各对应一个箭头，并可很好地与 Level 2 文本配合。未使用的文本不显示，但在切换布局时仍可用。

---

### CycleMatrix {#CycleMatrix}
用于展示循环进程中与中心思想的关系。前四行 Level 1 文本对应楔形或饼形，Level 2 文本出现在楔形或饼形侧面的矩形中。未使用的文本不显示，但在切换布局时仍可用。

---

### DescendingBlockList {#DescendingBlockList}
用于显示相关想法或信息列表的组。文本形状按高度递减顺序排列，Level 1 文本垂直显示。

---

### DescendingProcess {#DescendingProcess}
用于显示递降的事件序列。第一行 Level 1 文本位于箭头顶部，最后一行 Level 1 文本显示在箭头底部。仅显示前七个 Level 1 项目。适合少量至中等量的文本。

---

### DetailedProcess {#DetailedProcess}
用于在大量 Level 2 文本的情况下展示阶段性进展。

---

### DivergingArrows {#DivergingArrows}
用于展示从中心源向外扩展的想法或概念。仅使用 Level 1 文本时效果最佳。

---

### DivergingRadial {#DivergingRadial}
用于展示围绕中心思想的循环关系。第一行 Level 1 文本对应中心圆形。强调周围的圆形而非中心思想。未使用的文本不显示，但在切换布局时仍可用。

---

### Equation {#Equation}
用于展示描绘计划或结果的顺序步骤或任务。最后一行 Level 1 文本出现在等号 (=) 之后。仅使用 Level 1 文本时效果最佳。

---

### FramedTextPicture {#FramedTextPicture}
用于在框架中显示带有对应 Level 1 文本的图片。

---

### Funnel {#Funnel}
用于展示信息过滤或各部分合并为整体的过程。强调最终结果。最多可包含四行 Level 1 文本；第四行 Level 1 文本显示在漏斗下方，其余行对应圆形。未使用的文本不显示，但在切换布局时仍可用。

---

### Gear {#Gear}
用于展示相互锁定的想法。前三行 Level 1 文本对应齿轮形状，其对应的 Level 2 文本出现在齿轮旁边的矩形中。未使用的文本不显示，但在切换布局时仍可用。

---

### GridMatrix {#GridMatrix}
用于展示概念在两个轴上的布局。强调各个组件而非整体。前四行 Level 1 文本显示在四个象限中。未使用的文本不显示，但在切换布局时仍可用。

---

### GroupedList {#GroupedList}
用于显示信息的组和子组，或任务、过程或工作流的步骤和子步骤。Level 1 文本对应顶层水平形状，Level 2 文本对应每个相关顶层形状下的垂直子步骤。适用于强调子组或子步骤、层级信息或多列表信息。

---

### HalfCircleOrganizationChart {#HalfCircleOrganizationChart}
用于展示组织中的层级信息或汇报关系。此布局提供助理形状和组织图悬挂布局。

---

### HexagonCluster {#HexagonCluster}
用于展示带有描述性文本的图片。小六边形表示图片和文本对。适合少量文本。

---

### Hierarchy {#Hierarchy}
用于展示从上到下的层级关系。

---

### HierarchyList {#HierarchyList}
用于展示跨组的层级关系，也可用于分组或列出信息。

---

### HorizontalBulletList {#HorizontalBulletList}
用于展示非顺序或分组的信息列表。适合大量文本。所有文本具有相同的强调程度，且不暗示方向。

---

### HorizontalHierarchy {#HorizontalHierarchy}
用于水平展示层级关系。适用于决策树。

---

### HorizontalLabeledHierarchy {#HorizontalLabeledHierarchy}
用于水平展示并按层级分组的层级关系。强调标题或 Level 1 文本。第一行 Level 1 文本出现在层级起始形状中，第二行及后续所有 Level 1 文本出现在高矩形的顶部。

---

### HorizontalMultiLevelHierarchy {#HorizontalMultiLevelHierarchy}
用于水平展示大量层级信息。层级顶部以垂直方式显示。此布局支持层级的多级展示。

---

### HorizontalOrganizationChart {#HorizontalOrganizationChart}
用于水平展示组织中的层级信息或汇报关系。此布局提供助理形状和组织图悬挂布局。

---

### HorizontalPictureList {#HorizontalPictureList}
用于以非顺序或分组方式展示信息，并强调相关图片。顶层形状设计用于容纳图片。

---

### IncreasingArrowsProcess {#IncreasingArrowsProcess}
用于展示过程中的顺序和重叠步骤。限于五个 Level 1 项目。Level 2 可包含大量文本。

---

### IncreasingCircleProcess {#IncreasingCircleProcess}
用于展示一系列步骤，圆形内部随每一步递增。限于七个 Level 1 步骤，但 Level 2 项目数量不限。适合大量 Level 2 文本。

---

### InvertedPyramid {#InvertedPyramid}
用于展示比例、相互关联或层级关系，最大组件在顶部并逐渐收窄。Level 1 文本出现在金字塔段落中，Level 2 文本出现在每段旁边的形状中。

---

### LabeledHierarchy {#LabeledHierarchy}
用于从上到下展示层级关系并按层级分组。强调标题或 Level 1 文本。第一行 Level 1 文本出现在层级起始形状中，所有后续 Level 1 文本出现在长矩形的左侧。

---

### LinearVenn {#LinearVenn}
用于展示序列中的重叠关系。仅使用 Level 1 文本时效果最佳。

---

### LinedList {#LinedList}
用于将大量文本划分为类别和子类别。适合多层级文本。相同层级的文本之间以线分隔。

---

### MultidirectionalCycle {#MultidirectionalCycle}
用于表示可在任意方向发生的持续阶段、任务或事件序列。

---

### NameandTitleOrganizationChart {#NameandTitleOrganizationChart}
用于展示组织中的层级信息或汇报关系。要在标题框中输入文本，请直接在较小的矩形形状中键入。此布局提供助理形状和组织图悬挂布局。

---

### NestedTarget {#NestedTarget}
用于展示包含关系。前三行 Level 1 文本对应形状左上角的文本，Level 2 文本对应较小的形状。最适合使用最少的 Level 2 文本行。未使用的文本不显示，但在切换布局时仍可用。

---

### NondirectionalCycle {#NondirectionalCycle}
用于在循环流中表示持续的阶段、任务或事件序列。每个形状具有相同的重要性。适用于不需要指示方向的情况。

---

### OpposingArrows {#OpposingArrows}
用于展示两个相对的想法或从中心点发散的概念。前两行 Level 1 文本各对应一个箭头。未使用的文本不显示，但在切换布局时仍可用。

---

### OpposingIdeas {#OpposingIdeas}
用于展示两个相对或对立的想法。可以有一个或两个 Level 1 项目。每个 Level 1 文本可包含多个子层级。适合大量文本。

---

### OrganizationChart {#OrganizationChart}
用于展示组织中的层级信息或汇报关系。此布局提供助理形状和组织图悬挂布局。

---

### PhasedProcess {#PhasedProcess}
用于展示过程的三个阶段。限于三个 Level 1 项目。前两个 Level 1 项目各可包含四个 Level 2 项目，第三个 Level 1 项目可包含不限数量的 Level 2 项目。适合少量文本。

---

### PictureAccentBlocks {#PictureAccentBlocks}
用于从角落开始以块状展示一组图片。相应的文本垂直显示。适合作为标题或副标题幻灯片的点缀，或文档的章节分隔。
### PictureAccentList {#PictureAccentList}
用于显示分组或相关信息。左上角的小形状用于放置图片。强调 Level 2 文本高于 Level 1 文本，是大量 Level 2 文本的良好选择。

---

### PictureAccentProcess {#PictureAccentProcess}
用于显示任务、过程或工作流中的顺序步骤。背景中的矩形形状用于放置图片。

---

### PictureCaptionList {#PictureCaptionList}
用于显示非顺序或分组的信息块。顶部形状用于放置图片，图片相对于文本更为突出。适用于带有简短文字说明的图片。

---

### PictureGrid {#PictureGrid}
用于在方形网格上排列图片。最适合少量的 Level 1 文本，文本显示在图片上方。

---

### PictureLineup {#PictureLineup}
用于并排显示一系列图片。Level 1 文本位于图片顶部。Level 2 文本位于图片下方。

---

### PictureStrips {#PictureStrips}
用于从上到下显示一系列图片，并在每张图片旁边显示 Level 1 文本。

---

### PieProcess {#PieProcess}
用于显示过程中的步骤，每个饼图切片按大小递增，最多七个形状。Level 1 文本垂直显示。

---

### PlusandMinus {#PlusandMinus}
用于展示两个想法的利与弊。每个 Level 1 文本可包含多个子层级。适合大量文本。限于两个 Level 1 项目。

---

### ProcessArrows {#ProcessArrows}
用于展示说明过程或工作流的信息。Level 1 文本出现在圆形形状中，Level 2 文本出现在箭头形状中。最适合文本最少且强调移动或方向的情况。

---

### ProcessList {#ProcessList}
用于展示任务、过程或工作流中的多个信息组或步骤及子步骤。Level 1 文本对应顶部水平形状，Level 2 文本对应每个相关顶部形状下方的垂直子步骤。

---

### PyramidList {#PyramidList}
用于展示比例、相互关联或层级关系。文本显示在金字塔背景顶部的矩形形状中。

---

### RadialCluster {#RadialCluster}
用于展示与中心思想或主题相关的数据。顶部的 Level 1 文本位于中心。Level 2 文本出现在周围形状中。可容纳最多七个 Level 2 形状。未使用的文本不显示，但在切换布局时仍可用。最适合少量文本。

---

### RadialCycle {#RadialCycle}
用于展示与中心思想的关系。既强调中心圆圈中的信息，也强调外环圆圈中的信息如何贡献于中心思想。第一行 Level 1 文本对应中心圆圈，其 Level 2 文本对应外环圆圈。未使用的文本不显示，但在切换布局时仍可用。

---

### RadialList {#RadialList}
用于展示与中心思想的循环关系。中心形状可放置图片。Level 1 文本出现在较小的圆圈中，相关的 Level 2 文本出现在这些圆圈的侧面。

---

### RadialVenn {#RadialVenn}
用于展示重叠关系以及与中心思想的循环关系。第一行 Level 1 文本对应中心形状，Level 2 文本对应周围的圆形形状。未使用的文本不显示，但在切换布局时仍可用。

---

### RandomToResultProcess {#RandomToResultProcess}
用于通过一系列步骤展示多个混乱想法如何汇聚为统一目标或想法。支持多个 Level 1 文本项，但首尾对应的 Level 1 形状固定。最适合少量 Level 1 文本和中等量 Level 2 文本。

---

### RepeatingBendingProcess {#RepeatingBendingProcess}
用于展示任务、过程或工作流中的进展或顺序步骤。最大化形状的水平和垂直显示空间。

---

### ReverseList {#ReverseList}
用于在两个项目之间切换。仅显示前两个文本项目，每个项目可包含大量文本。适合展示两个项目之间的变化或顺序的转变。

---

### SegmentedCycle {#SegmentedCycle}
用于在循环流中展示进展或一系列阶段、任务或事件。强调相互关联的部分。前七行 Level 1 文本对应楔形或饼形。未使用的文本不显示，但在切换布局时仍可用。

---

### SegmentedProcess {#SegmentedProcess}
用于展示任务、过程或工作流中的进展或顺序步骤。强调 Level 2 文本，因为每行文本出现在单独的形状中。

---

### SegmentedPyramid {#SegmentedPyramid}
用于展示包含、比例或相互关联的关系。前九行 Level 1 文本出现在三角形状中。未使用的文本不显示，但在切换布局时仍可用。最适合仅使用 Level 1 文本。

---

### SnapshotPictureList {#SnapshotPictureList}
用于展示带说明文字的图片。Level 2 文本可显示信息列表。适合大量文本。

---

### SpiralPicture {#SpiralPicture}
用于展示最多五张图片及其对应的 Level 1 标题，图片螺旋向中心排列。

---

### SquareAccentList {#SquareAccentList}
用于展示按类别划分的信息列表。Level 2 文本出现在小方形旁边。适合大量 Level 2 文本。

---

### StackedList {#StackedList}
用于展示任务、过程或工作流中的信息组或步骤。圆形形状包含 Level 1 文本，对应的矩形包含 Level 2 文本。适合大量细节和最少的 Level 1 文本。

---

### StackedVenn {#StackedVenn}
用于展示重叠关系。是强调增长或分层的良好选择。最适合仅使用 Level 1 文本。前七行 Level 1 文本对应一个圆形形状。未使用的文本不显示，但在切换布局时仍可用。

---

### StaggeredProcess {#StaggeredProcess}
用于展示向下的阶段进展。前五行 Level 1 文本对应矩形。未使用的文本不显示，但在切换布局时仍可用。

---

### StepDownProcess {#StepDownProcess}
用于展示具有多个步骤和子步骤的下降过程。最适合少量文本。

---

### StepUpProcess {#StepUpProcess}
用于展示上升的步骤系列或信息列表。

---

### SubStepProcess {#SubStepProcess}
用于展示在每个 Level 1 文本实例之间有子步骤的多步骤过程。最适合少量文本，且限于七个 Level 1 步骤。每个 Level 1 步骤可拥有无限的子步骤。

---

### TableHierarchy {#TableHierarchy}
用于展示从上到下构建的信息组及其层级关系。此布局不包含连接线。

---

### TableList {#TableList}
用于展示等值的分组或相关信息。第一行 Level 1 文本对应顶部形状，其 Level 2 文本用于后续列表。

---

### TargetList {#TargetList}
用于展示相互关联或重叠的信息。前七行 Level 1 文本出现在矩形形状中。未使用的文本不显示，但在切换布局时仍可用。适合同时使用 Level 1 和 Level 2 文本。

---

### TextCycle {#TextCycle}
用于在循环流中表示持续的阶段、任务或事件序列。强调箭头或流动而非阶段或步骤。最适合仅使用 Level 1 文本。

---

### TitlePictureLineup {#TitlePictureLineup}
用于展示每张图片都有自己的标题和说明的一系列图片。Level 1 文本出现在图片上方的框中。Level 2 文本出现在图片下方。

---

### TitledMatrix {#TitledMatrix}
用于展示四个象限与整体的关系。第一行 Level 1 文本对应中心形状，前四行 Level 2 文本出现在象限中。未使用的文本不显示，但在切换布局时仍可用。

---

### TitledPictureAccentList {#TitledPictureAccentList}
用于展示每个 Level 2 文本都有配图的列表。Level 1 文本显示在列表顶部的单独框中。

---

### TitledPictureBlocks {#TitledPictureBlocks}
用于展示一系列图片。Level 1 文本显示在每张图片上方。Level 2 文本显示在侧面并稍微重叠每张图片。

---

### TrapezoidList {#TrapezoidList}
用于展示等值的分组或相关信息。适合大量文本。

---

### UpwardArrow {#UpwardArrow}
用于展示在任务、过程或工作流中向上趋势的进展或步骤。前五行 Level 1 文本对应箭头上的一点。最适合最少文本。未使用的文本不显示，但在切换布局时仍可用。

---

### VerticalAccentList {#VerticalAccentList}
用于展示信息列表。Level 2 文本出现在垂直箭头形状上的矩形中。强调 Level 2 文本高于 Level 1 文本，是中等量 Level 2 文本的良好选择。

---

### VerticalArrowList {#VerticalArrowList}
用于展示在任务、过程或工作流中朝向共同目标的进展或顺序步骤。适合项目符号信息列表。

---

### VerticalBendingProcess {#VerticalBendingProcess}
用于展示任务、过程或工作流中的进展或顺序步骤。最大化形状的水平和垂直显示空间。比起方向或移动，更强调形状之间的相互关系。

---

### VerticalBlockList {#VerticalBlockList}
用于展示任务、过程或工作流中的信息组或步骤。适合大量 Level 2 文本。是拥有主点和多个子点的文本的良好选择。

---

### VerticalBoxList {#VerticalBoxList}
用于展示多个信息组，尤其是包含大量 Level 2 文本的组。是项目符号信息列表的良好选择。

---

### VerticalBulletList {#VerticalBulletList}
用于展示非顺序或分组的信息块。适合标题或顶层信息较长的列表。

---

### VerticalChevronList {#VerticalChevronList}
用于展示任务、过程或工作流中的进展或顺序步骤，或强调移动或方向。强调 Level 2 文本高于 Level 1 文本，是大量 Level 2 文本的良好选择。

---

### VerticalCircleList {#VerticalCircleList}
用于展示顺序或分组的数据。最适合 Level 1 文本，文本显示在大型圆形旁边。较低层级的文本以较小的圆形分隔。

---

### VerticalCurvedList {#VerticalCurvedList}
用于展示曲线形的信息列表。要向强调圆形添加图片，请使用图片填充。

---

### VerticalEquation {#VerticalEquation}
用于展示描述计划或结果的顺序步骤或任务。最后一行 Level 1 文本出现在箭头后面。最适合仅使用 Level 1 文本。

---

### VerticalPictureAccentList {#VerticalPictureAccentList}
用于展示非顺序或分组的信息块。小圆形设计用于放置图片。

---

### VerticalPictureList {#VerticalPictureList}
用于展示非顺序或分组的信息块。左侧的小形状设计用于放置图片。

---

### VerticalProcess {#VerticalProcess}
Use to show a progression or sequential steps in a task, process, or workflow from top to bottom. Works best with Level 1 text, since the vertical space is limited.

---

### Custom {#Custom}
表示具有自定义布局模板的 SmartArt 图表

---

### PictureOrganizationChart {#PictureOrganizationChart}
用于在组织中显示层级信息或汇报关系，并配以相应的图片。此布局提供助理形状和 Org Chart hanging layouts。

---