---
title: SmartArtLayoutType
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/smartartlayouttype/
---

## SmartArtLayoutType class

 Represents layout type of a SmartArt diagram.
 

## Constants

| Name | Value | Description |
| --- | --- | --- |
| [AccentProcess](#AccentProcess) | 0 | Use to show a progression, a timeline, or sequential steps in a task, process, or workflow. Works well for illustrating both Level 1 and Level 2 text. |
| [AccentedPicture](#AccentedPicture) | 1 | Use to show a central, photographic idea with related ideas on the side. The top Level 1 text appears over the central picture. Corresponding text for other Level 1 shapes appear next to the small circular pictures. This layout also works well with no text. |
| [AlternatingFlow](#AlternatingFlow) | 2 | Use to show groups of information or sequential steps in a task, process, or workflow. Emphasizes the interaction or relationships among the groups of information. |
| [AlternatingHexagons](#AlternatingHexagons) | 3 | Use to represent a series of interconnected ideas. Level 1 text appears inside the hexagons. Level 2 text appears outside the shapes. |
| [AlternatingPictureBlocks](#AlternatingPictureBlocks) | 4 | Use to show a series of pictures from top to bottom. Text appears alternately on the right or left of the picture. |
| [AlternatingPictureCircles](#AlternatingPictureCircles) | 5 | Use to show a set of pictures with text. The corresponding text appears in the central circles with the images alternating from left to right. |
| [ArrowRibbon](#ArrowRibbon) | 6 | Use to show either related or contrasting concepts with some connection, such as opposing forces. The first two lines of Level 1 text are used for text in the arrows. Unused text does not appear, but remains available if you switch layouts. |
| [AscendingPictureAccentProcess](#AscendingPictureAccentProcess) | 7 | Use to show an ascending series of pictures with descriptive text. Works best with a small amount of text. |
| [Balance](#Balance) | 8 | Use to compare or show the relationship between two ideas. Each of the first two lines of Level 1 text corresponds to text at the top of one side of the center point. Emphasizes Level 2 text, which is limited to four shapes on each side of the center point. The balance tips towards the side with the most shapes containing Level 2 text. Unused text does not appear, but remains available if you switch layouts. |
| [BasicBendingProcess](#BasicBendingProcess) | 9 | Use to show a progression or sequential steps in a task, process, or workflow. Maximizes both horizontal and vertical display space for shapes. |
| [BasicBlockList](#BasicBlockList) | 10 | Use to show non-sequential or grouped blocks of information. Maximizes both horizontal and vertical display space for shapes. |
| [BasicChevronProcess](#BasicChevronProcess) | 11 | Use to show a progression; a timeline; sequential steps in a task, process, or workflow; or to emphasize movement or direction. Level 1 text appears inside an arrow shape while Level 2 text appears below the arrow shapes. |
| [BasicCycle](#BasicCycle) | 12 | Use to represent a continuing sequence of stages, tasks, or events in a circular flow. Emphasizes the stages or steps rather than the connecting arrows or flow. Works best with Level 1 text only. |
| [BasicMatrix](#BasicMatrix) | 13 | Use to show the relationship of components to a whole in quadrants. The first four lines of Level 1 text appear in the quadrants. Unused text does not appear, but remains available if you switch layouts. |
| [BasicPie](#BasicPie) | 14 | Use to show how individual parts form a whole. The first seven lines of Level 1 text correspond to the evenly distributed wedge or pie shapes. The top Level 1 text shape appears outside of the rest of the pie for emphasis. Unused text does not appear, but remains available if you switch layouts. |
| [BasicProcess](#BasicProcess) | 15 | Use to show a progression or sequential steps in a task, process, or workflow. |
| [BasicPyramid](#BasicPyramid) | 16 | Use to show proportional, interconnected, or hierarchical relationships with the largest component on the bottom and narrowing up. Level 1 text appears in the pyramid segments and Level 2 text appears in shapes alongside each segment. |
| [BasicRadial](#BasicRadial) | 17 | Use to show the relationship to a central idea in a cycle. The first line of Level 1 text corresponds to the central shape, and its Level 2 text corresponds to the surrounding circular shapes. Unused text does not appear, but remains available if you switch layouts. |
| [BasicTarget](#BasicTarget) | 18 | Use to show containment, gradations, or hierarchical relationships. The first five lines of Level 1 text are associated with a circle. Unused text does not appear, but remains available if you switch layouts. |
| [BasicTimeline](#BasicTimeline) | 19 | Use to show sequential steps in a task, process, or workflow, or to show timeline information. Works well with both Level 1 and Level 2 text. |
| [BasicVenn](#BasicVenn) | 20 | Use to show overlapping or interconnected relationships. The first seven lines of Level 1 text correspond with a circle. If there are four or fewer lines of Level 1 text, the text is inside the circles. If there are more than four lines of Level 1 text, the text is outside of the circles. Unused text does not appear, but remains available if you switch layouts. |
| [BendingPictureAccentList](#BendingPictureAccentList) | 21 | Use to show non-sequential or grouped blocks of information. The small circular shapes are designed to contain pictures. Works well for illustrating both Level 1 and Level 2 text. Maximizes both horizontal and vertical display space for shapes. |
| [BendingPictureBlocks](#BendingPictureBlocks) | 22 | Use to show a series of pictures. The box covering the bottom corner can contain small amounts of text. |
| [BendingPictureCaption](#BendingPictureCaption) | 23 | Use to show a sequential series of pictures. The box covering the bottom corner can contain small amounts of text. |
| [BendingPictureCaptionList](#BendingPictureCaptionList) | 24 | Use to show a series of pictures. The title and description appear in a callout shape under each picture. |
| [BendingPictureSemiTransparentText](#BendingPictureSemiTransparentText) | 25 | Use to show a series of pictures. A semi-transparent box covers the lower portion of the picture and contains all levels of text. |
| [BlockCycle](#BlockCycle) | 26 | Use to represent a continuing sequence of stages, tasks, or events in a circular flow. Emphasizes the stages or steps rather than the connecting arrows or flow. |
| [BubblePictureList](#BubblePictureList) | 27 | Use to show a series of pictures. Can contain up to eight Level 1 pictures. Unused text and pictures do not appear, but remain available if you switch layouts. Works best with small amounts of text. |
| [CaptionedPictures](#CaptionedPictures) | 28 | Use to show pictures with multiple levels of text. Works best with a small amount of Level 1 text and a medium amount of Level 2 text. |
| [ChevronList](#ChevronList) | 29 | Use to show a progression through several processes that make up an overall workflow. Also works for illustrating contrasting processes. The Level 1 text corresponds to the first arrow shape on the left, while the Level 2 text corresponds to horizontal sub-steps for each shape that contains Level 1 text. |
| [CircleAccentTimeline](#CircleAccentTimeline) | 30 | Use to show a series of events or timeline information. Level 1 text appears next to larger circular shapes. Level 2 text appears next to smaller circular shapes. |
| [CircleArrowProcess](#CircleArrowProcess) | 31 | Use to show sequential items with supporting text for each item. This diagram works best with small amounts of Level 1 text. |
| [CirclePictureHierarchy](#CirclePictureHierarchy) | 32 | Use to show hierarchical information or reporting relationships in an organization. Pictures appear in circles and corresponding text appears next to the pictures. |
| [CircleRelationship](#CircleRelationship) | 33 | Use to show the relationship to or from a central idea. Level 2 text is added non-sequentially and is limited to five items. There can only be one Level 1 item. |
| [CircularBendingProcess](#CircularBendingProcess) | 34 | Use to show a long or non-linear sequence or steps in a task, process, or workflow. Works best with Level 1 text only. Maximizes both horizontal and vertical display space for shapes. |
| [CircularPictureCallout](#CircularPictureCallout) | 35 | Use to show a central idea and sub-ideas or related items. The text for the first picture covers the lower portion of the picture. The corresponding text for other Level 1 shapes appears next to the small circular pictures. This diagram also works well with no text. |
| [ClosedChevronProcess](#ClosedChevronProcess) | 36 | Use to show a progression, a timeline, or sequential steps in a task, process, or workflow, or to emphasize movement or direction. Can be used to emphasize information in the starting shape. Works best with Level 1 text only. |
| [ContinuousArrowProcess](#ContinuousArrowProcess) | 37 | Use to show a timeline or sequential steps in a task, process, or workflow. Works best with Level 1 text because each line of Level 1 text appears inside the arrow shape. Level 2 text appears outside the arrow shape. |
| [ContinuousBlockProcess](#ContinuousBlockProcess) | 38 | Use to show a progression or sequential steps in a task, process, or workflow. Works best with minimal Level 1 and Level 2 text. |
| [ContinuousCycle](#ContinuousCycle) | 39 | Use to represent a continuing sequence of stages, tasks, or events in a circular flow. Emphasizes the connection between all components. Works best with Level 1 text only. |
| [ContinuousPictureList](#ContinuousPictureList) | 40 | Use to show groups of interconnected information. The circular shapes are designed to contain pictures. |
| [ConvergingArrows](#ConvergingArrows) | 41 | Use to show ideas or concepts that converge to a central point. Works best with Level 1 text only. |
| [ConvergingRadial](#ConvergingRadial) | 42 | Use to show relationships of concepts or components to a central idea in a cycle. The first line of Level 1 text corresponds to the central circular shape and the lines of Level 2 text correspond to the surrounding rectangular shapes. Unused text does not appear, but remains available if you switch layouts. |
| [CounterbalanceArrows](#CounterbalanceArrows) | 43 | Use to show two opposing ideas or concepts. Each of the first two lines of Level 1 text corresponds to an arrow and works well with Level 2 text. Unused text does not appear, but remains available if you switch layouts. |
| [CycleMatrix](#CycleMatrix) | 44 | Use to show the relationship to a central idea in a cyclical progression. Each of the first four lines of Level 1 text corresponds to a wedge or pie shape, and Level 2 text appears in a rectangular shape to the side of the wedge or pie shape. Unused text does not appear, but remains available if you switch layouts. |
| [DescendingBlockList](#DescendingBlockList) | 45 | Use to show groups of related ideas or lists of information. The text shapes decrease in height sequentially, and the Level 1 text displays vertically. |
| [DescendingProcess](#DescendingProcess) | 46 | Use to show a descending series of events. The first Level 1 text is at the top of arrow, and the last Level 1 text displays at the bottom of the arrow. Only the first seven Level 1 items appear. Works best with small to medium amounts of text. |
| [DetailedProcess](#DetailedProcess) | 47 | Use with large amounts of Level 2 text to show a progression through stages. |
| [DivergingArrows](#DivergingArrows) | 48 | Use to show ideas or concepts that progress outward from a central source. Works best with Level 1 text only. |
| [DivergingRadial](#DivergingRadial) | 49 | Use to show relationships to a central idea in a cycle. The first Level 1 line of text corresponds to the central circular shape. Emphasizes the surrounding circles rather than the central idea. Unused text does not appear, but remains available if you switch layouts. |
| [Equation](#Equation) | 50 | Use to show sequential steps or tasks that depict a plan or result. The last Level 1 line of text appears after the equals sign (=).Works best with Level 1 text only. |
| [FramedTextPicture](#FramedTextPicture) | 51 | Use to show pictures with corresponding Level 1 text displayed in a frame. |
| [Funnel](#Funnel) | 52 | Use to show the filtering of information or how parts merge into a whole. Emphasizes the final outcome. Can contain up to four lines of Level 1 text; the last of these four Level 1 text lines appears below the funnel and the other lines correspond to a circular shape. Unused text does not appear, but remains available if you switch layouts. |
| [Gear](#Gear) | 53 | Use to show interlocking ideas. Each of the first three lines of Level 1 text corresponds to a gear shape, and their corresponding Level 2 text appears in rectangles next to the gear shape. Unused text does not appear, but remains available if you switch layouts. |
| [GridMatrix](#GridMatrix) | 54 | Use to show the placement of concepts along two axes. Emphasizes the individual components rather than the whole. The first four lines of Level 1 text appear in the quadrants. Unused text does not appear, but remains available if you switch layouts. |
| [GroupedList](#GroupedList) | 55 | Use to show groups and sub-groups of information, or steps and sub-steps in a task, process, or workflow. Level 1 text corresponds to the top level horizontal shapes, and Level 2 text corresponds to vertical sub-steps under each related top level shape. Works well for emphasizing sub-groups or sub-steps, hierarchical information, or multiple lists of information. |
| [HalfCircleOrganizationChart](#HalfCircleOrganizationChart) | 56 | Use to show hierarchical information or reporting relationships in an organization. The assistant shapes and Org Chart hanging layouts are available with this layout. |
| [HexagonCluster](#HexagonCluster) | 57 | Use to show pictures with associated descriptive text. Small hexagons indicate the picture and text pair. Works best with small amounts of text. |
| [Hierarchy](#Hierarchy) | 58 | Use to show hierarchical relationships progressing from top to bottom. |
| [HierarchyList](#HierarchyList) | 59 | Use to show hierarchical relationships progressing across groups. Can also be used to group or list information. |
| [HorizontalBulletList](#HorizontalBulletList) | 60 | Use to show non-sequential or grouped lists of information. Works well with large amounts of text. All text has the same level of emphasis, and direction is not implied. |
| [HorizontalHierarchy](#HorizontalHierarchy) | 61 | Use to show hierarchical relationships progressing horizontally. Works well for decision trees. |
| [HorizontalLabeledHierarchy](#HorizontalLabeledHierarchy) | 62 | Use to show hierarchical relationships progressing horizontally and grouped hierarchically. Emphasizes heading or level 1 text. The first line of Level 1 text appears in the shape at the beginning of the hierarchy, and the second and all subsequent lines of Level 1 text appear at the top of the tall rectangles. |
| [HorizontalMultiLevelHierarchy](#HorizontalMultiLevelHierarchy) | 63 | Use to show large amounts of hierarchical information progressing horizontally. The top of the hierarchy is displayed vertically. This layout supports many levels in the hierarchy. |
| [HorizontalOrganizationChart](#HorizontalOrganizationChart) | 64 | Use to show hierarchical information horizontally or reporting relationships in an organization. The assistant shape and the Org Chart hanging layouts are available with this layout. |
| [HorizontalPictureList](#HorizontalPictureList) | 65 | Use to show non-sequential or grouped information with an emphasis on related pictures. The top shapes are designed to contain pictures. |
| [IncreasingArrowsProcess](#IncreasingArrowsProcess) | 66 | Use to show sequential and overlapping steps in a process. Limited to five Level 1 items. Level 2 can contain large amounts of text. |
| [IncreasingCircleProcess](#IncreasingCircleProcess) | 67 | Use to show a series of steps, with the interior of the circle increasing with each step. Limited to seven Level 1 steps but unlimited Level 2 items. Works well with large amounts of Level 2 text. |
| [InvertedPyramid](#InvertedPyramid) | 68 | Use to show proportional, interconnected, or hierarchical relationships with the largest component on the top and narrowing down. Level 1 text appears in the pyramid segments and Level 2 text appears in shapes alongside each segment. |
| [LabeledHierarchy](#LabeledHierarchy) | 69 | Use to show hierarchical relationships progressing from top to bottom and grouped hierarchically. Emphasizes heading or level 1 text. The first line of Level 1 text appears in the shape at the beginning of the hierarchy, and all subsequent lines of Level 1 text appear to the left of the long rectangles. |
| [LinearVenn](#LinearVenn) | 70 | Use to show overlapping relationships in a sequence. Works best with Level 1 text only. |
| [LinedList](#LinedList) | 71 | Use to show large amounts of text divided into categories and subcategories. Works well with multiple levels of text. Text at the same level is separated by lines. |
| [MultidirectionalCycle](#MultidirectionalCycle) | 72 | Use to represent a continuing sequence of stages, tasks, or events that can occur in any direction. |
| [NameandTitleOrganizationChart](#NameandTitleOrganizationChart) | 73 | Use to show hierarchical information or reporting relationships in an organization. To enter text in the title box, type directly in the smaller rectangular shape. The assistant shape and Org Chart hanging layouts are available with this layout. |
| [NestedTarget](#NestedTarget) | 74 | Use to show containment relationships. Each of the first three lines of Level 1 text correspond to the upper left text in the shapes, and Level 2 text corresponds to the smaller shapes. Works best with minimal Level 2 lines of text. Unused text does not appear, but remains available if you switch layouts. |
| [NondirectionalCycle](#NondirectionalCycle) | 75 | Use to represent a continuing sequence of stages, tasks, or events in a circular flow. Each shape has the same level of importance. Works well when direction does not need to be indicated. |
| [OpposingArrows](#OpposingArrows) | 76 | Use to show two opposing ideas, or ideas that diverge from a central point. Each of the first two lines of Level 1 text corresponds to an arrow. Unused text does not appear, but remains available if you switch layouts. |
| [OpposingIdeas](#OpposingIdeas) | 77 | Use to show two opposing or contrasting ideas. Can have one or two Level 1 items. Each Level 1 text can contain multiple sub-levels. Works well with large amounts of text. |
| [OrganizationChart](#OrganizationChart) | 78 | Use to show hierarchical information or reporting relationships in an organization. The assistant shape and the Org Chart hanging layouts are available with this layout. |
| [PhasedProcess](#PhasedProcess) | 79 | Use to show three phases of a process. Limited to three Level 1 items. The first two Level 1 items can each contain four Level 2 items, and the third Level 1 item can contain an unlimited number of Level 2 items. Works best with small amounts of text. |
| [PictureAccentBlocks](#PictureAccentBlocks) | 80 | Use to show a group of pictures in blocks starting from the corner. The corresponding text displays vertically. Works well as an accent on title or sub-title slides or for section breaks of a document. |
| [PictureAccentList](#PictureAccentList) | 81 | Use to show grouped or related information. The small shapes on the upper corners are designed to contain pictures. Emphasizes Level 2 text over Level 1 text, and is a good choice for large amounts of Level 2 text. |
| [PictureAccentProcess](#PictureAccentProcess) | 82 | Use to show sequential steps in a task, process, or workflow. The rectangular shapes in the background are designed to contain pictures. |
| [PictureCaptionList](#PictureCaptionList) | 83 | Use to show non-sequential or grouped blocks of information. The top shapes are designed to contain pictures and pictures are emphasized over text. Works well for pictures with short text captions. |
| [PictureGrid](#PictureGrid) | 84 | Use to show pictures laid out on a square grid. Best with a small amount of Level 1 text, which appears above the picture. |
| [PictureLineup](#PictureLineup) | 85 | Use to show a series of pictures side by side. Level 1 text covers the top of the picture. Level 2 text appears below the picture. |
| [PictureStrips](#PictureStrips) | 86 | Use to show a series of pictures from top to bottom with Level 1 text beside each. |
| [PieProcess](#PieProcess) | 87 | Use to show steps in a process with each pie slice increasing in size up to seven shapes. Level 1 text displays vertically. |
| [PlusandMinus](#PlusandMinus) | 88 | Use to show the pros and cons of two ideas. Each Level 1 text can contain multiple sub-levels. Works well with large amounts of text. Limited to two Level 1 items. |
| [ProcessArrows](#ProcessArrows) | 89 | Use to show information illustrating a process or workflow. Level 1 text appears in the circular shapes and Level 2 text appears in the arrow shapes. Works best for minimal text and to emphasize movement or direction. |
| [ProcessList](#ProcessList) | 90 | Use to show multiple groups of information or steps and sub-steps in a task, process, or workflow. Level 1 text corresponds to the top horizontal shapes, and Level 2 text corresponds to vertical sub-steps under each related top level shape. |
| [PyramidList](#PyramidList) | 91 | Use to show proportional, interconnected, or hierarchical relationships. Text appears in the rectangular shapes on top of the pyramid background. |
| [RadialCluster](#RadialCluster) | 92 | Use to show data that relates to a central idea or theme. The top Level 1 text appears in the center. Level 2 text appears in surrounding shapes. Can contain up to seven Level 2 shapes. Unused text does not appear, but remains available if you switch layouts. Works best with small amounts of text. |
| [RadialCycle](#RadialCycle) | 93 | Use to show the relationship to a central idea. Emphasizes both information in the center circle and how information in the outer ring of circles contributes to the central idea. The first Level 1 line of text corresponds to the central circle, and its Level 2 text corresponds to the outer ring of circles. Unused text does not appear, but remains available if you switch layouts. |
| [RadialList](#RadialList) | 94 | Use to show relationships to a central idea in a cycle. The center shape can contain a picture. Level 1 text appears in the smaller circles and any related Level 2 text appears to the side of the smaller circles. |
| [RadialVenn](#RadialVenn) | 95 | Use to show both overlapping relationships and the relationship to a central idea in a cycle. The first line of Level 1 text corresponds to the central shape and the lines of Level 2 text correspond to the surrounding circular shapes. Unused text does not appear, but remains available if you switch layouts. |
| [RandomToResultProcess](#RandomToResultProcess) | 96 | Use to show, through a series of steps, how several chaotic ideas can result in a unified goal or idea. Supports multiple items of Level 1 text, but the first and last Level 1 corresponding shapes are fixed. Works best with small amounts of Level 1 text and medium amounts of Level 2 text. |
| [RepeatingBendingProcess](#RepeatingBendingProcess) | 97 | Use to show a progression or sequential steps in a task, process, or workflow. Maximizes both horizontal and vertical display space for shapes. |
| [ReverseList](#ReverseList) | 98 | Use to change between two items. Only the first two items of text display, and each item can contain a large amount of text. Works well to show a change between two items or shift in order. |
| [SegmentedCycle](#SegmentedCycle) | 99 | Use to show a progression or a sequence of stages, tasks, or events in a circular flow. Emphasizes the interconnected pieces. Each of the first seven lines of Level 1 text corresponds to a wedge or pie shape. Unused text does not appear, but remains available if you switch layouts. |
| [SegmentedProcess](#SegmentedProcess) | 100 | Use to show a progression or sequential steps in a task, process, or workflow. Emphasizes Level 2 text, since each line appears in a separate shape. |
| [SegmentedPyramid](#SegmentedPyramid) | 101 | Use to show containment, proportional, or interconnected relationships. The first nine lines of Level 1 text appear in the triangular shapes. Unused text does not appear, but remains available if you switch layouts. Works best with Level 1 text only. |
| [SnapshotPictureList](#SnapshotPictureList) | 102 | Use to show pictures with explanatory text. Level 2 text can display lists of information. Works well with a large amount of text. |
| [SpiralPicture](#SpiralPicture) | 103 | Use to show a series of up to five pictures with corresponding Level 1 captions that spiral in to the center. |
| [SquareAccentList](#SquareAccentList) | 104 | Use to show lists of information divided into categories. Level 2 text appears beside a small square shape. Works well with large amounts of Level 2 text. |
| [StackedList](#StackedList) | 105 | Use to show groups of information or steps in a task, process, or workflow. Circular shapes contain Level 1 text, and the corresponding rectangles contain Level 2 text. Works well for numerous details and minimal Level 1 text. |
| [StackedVenn](#StackedVenn) | 106 | Use to show overlapping relationships. A good choice for emphasizing growth or gradation. Works best with Level 1 text only. The first seven lines of Level 1 text correspond to a circular shape. Unused text does not appear, but remains available if you switch layouts. |
| [StaggeredProcess](#StaggeredProcess) | 107 | Use to show a downward progression through stages. Each of the first five lines of Level 1 text corresponds with a rectangle. Unused text does not appear, but remains available if you switch layouts. |
| [StepDownProcess](#StepDownProcess) | 108 | Use to show a descending process with multiple steps and sub-steps. Works best with small amounts of text. |
| [StepUpProcess](#StepUpProcess) | 109 | Use to show an ascending series of steps or lists of information. |
| [SubStepProcess](#SubStepProcess) | 110 | Use to show a multi-step process with sub-steps between each instance of Level 1 text. Works best with small amounts of text and is limited to seven Level 1 steps. Each Level 1 step can have unlimited sub-steps. |
| [TableHierarchy](#TableHierarchy) | 111 | Use to show groups of information built from top to bottom, and the hierarchies within each group. This layout does not contain connecting lines. |
| [TableList](#TableList) | 112 | Use to show grouped or related information of equal value. The first Level 1 line of text corresponds to the top shape and its Level 2 text is used for the subsequent lists. |
| [TargetList](#TargetList) | 113 | Use to show interrelated or overlapping information. Each of the first seven lines of Level 1 text appears in the rectangular shape. Unused text does not appear, but remains available if you switch layouts. Works well with both Level 1 and Level 2 text. |
| [TextCycle](#TextCycle) | 114 | Use to represent a continuing sequence of stages, tasks, or events in a circular flow. Emphasizes the arrows or flow rather than the stages or steps. Works best with Level 1 text only. |
| [TitlePictureLineup](#TitlePictureLineup) | 115 | Use to show a series of pictures that each have their own title and description. Level 1 text appears in the box above the picture. Level 2 text appears below the picture. |
| [TitledMatrix](#TitledMatrix) | 116 | Use to show the relationships of four quadrants to a whole. The first line of Level 1 text corresponds to the central shape, and the first four lines of Level 2 text appear in the quadrants. Unused text does not appear, but remains available if you switch layouts. |
| [TitledPictureAccentList](#TitledPictureAccentList) | 117 | Use to show lists of information with an accent picture for each Level 2 text. Level 1 text displays in a separate box at the top of the list. |
| [TitledPictureBlocks](#TitledPictureBlocks) | 118 | Use to show a series of pictures. Level 1 text appears above each picture. Level 2 text appears to the side and slightly overlapping each picture. |
| [TrapezoidList](#TrapezoidList) | 119 | Use to show grouped or related information of equal value. Works well with large amounts of text. |
| [UpwardArrow](#UpwardArrow) | 120 | Use to show a progression or steps that trend upward in a task, process, or workflow. Each of the first five lines of Level 1 text corresponds to a point on the arrow. Works best with minimal text. Unused text does not appear, but remains available if you switch layouts. |
| [VerticalAccentList](#VerticalAccentList) | 121 | Use to show lists of information. Level 2 text appears in rectangular shapes over vertical chevrons. Emphasizes Level 2 text over Level 1 text, and is a good choice for medium amounts of Level 2 text. |
| [VerticalArrowList](#VerticalArrowList) | 122 | Use to show a progression or sequential steps in a task, process, or workflow that move toward a common goal. Works well for bulleted lists of information. |
| [VerticalBendingProcess](#VerticalBendingProcess) | 123 | Use to show a progression or sequential steps in a task, process, or workflow. Maximizes both horizontal and vertical display space for shapes. Places more emphasis on the interrelationships among the shapes than on direction or movement. |
| [VerticalBlockList](#VerticalBlockList) | 124 | Use to show groups of information or steps in a task, process, or workflow. Works well with large amounts of Level 2 text. A good choice for text with a main point and multiple sub-points. |
| [VerticalBoxList](#VerticalBoxList) | 125 | Use to show several groups of information, especially groups with large amounts of Level 2 text. A good choice for bulleted lists of information. |
| [VerticalBulletList](#VerticalBulletList) | 126 | Use to show non-sequential or grouped blocks of information. Works well for lists with long headings or top level information. |
| [VerticalChevronList](#VerticalChevronList) | 127 | Use to show a progression or sequential steps in a task, process, or workflow, or to emphasize movement or direction. Emphasizes Level 2 text over Level 1 text, and is a good choice for large amounts of Level 2 text. |
| [VerticalCircleList](#VerticalCircleList) | 128 | Use to show sequential or grouped data. Works best for Level 1 text, which displays next to a large circular shape. Lower levels of text are separated with smaller circular shapes. |
| [VerticalCurvedList](#VerticalCurvedList) | 129 | Use to show a curved list of information. To add pictures to the accent circle shapes, apply a picture fill. |
| [VerticalEquation](#VerticalEquation) | 130 | Use to show sequential steps or tasks that depict a plan or result. The last Level 1 line of text appears after the arrow. Works best with Level 1 text only. |
| [VerticalPictureAccentList](#VerticalPictureAccentList) | 131 | Use to show non-sequential or grouped blocks of information. The small circles are designed to contain pictures. |
| [VerticalPictureList](#VerticalPictureList) | 132 | Use to show non-sequential or grouped blocks of information. The small shapes on the left are designed to contain pictures. |
| [VerticalProcess](#VerticalProcess) | 133 | Use to show a progression or sequential steps in a task, process, or workflow from top to bottom. Works best with Level 1 text, since the vertical space is limited. |
| [Custom](#Custom) | 134 | Represents a SmartArt diagram with custom layout template |
| [PictureOrganizationChart](#PictureOrganizationChart) | 135 | Use to show hierarchical information or reporting relationships in an organization, with corresponding pictures. The assistant shape and Org Chart hanging layouts are available with this layout. |


---


### AccentProcess {#AccentProcess}
| AccentProcess| 0 | Use to show a progression, a timeline, or sequential steps in a task, process, or workflow. Works well for illustrating both Level 1 and Level 2 text. |


---

### AccentedPicture {#AccentedPicture}
| AccentedPicture| 1 | Use to show a central, photographic idea with related ideas on the side. The top Level 1 text appears over the central picture. Corresponding text for other Level 1 shapes appear next to the small circular pictures. This layout also works well with no text. |


---

### AlternatingFlow {#AlternatingFlow}
| AlternatingFlow| 2 | Use to show groups of information or sequential steps in a task, process, or workflow. Emphasizes the interaction or relationships among the groups of information. |


---

### AlternatingHexagons {#AlternatingHexagons}
| AlternatingHexagons| 3 | Use to represent a series of interconnected ideas. Level 1 text appears inside the hexagons. Level 2 text appears outside the shapes. |


---

### AlternatingPictureBlocks {#AlternatingPictureBlocks}
| AlternatingPictureBlocks| 4 | Use to show a series of pictures from top to bottom. Text appears alternately on the right or left of the picture. |


---

### AlternatingPictureCircles {#AlternatingPictureCircles}
| AlternatingPictureCircles| 5 | Use to show a set of pictures with text. The corresponding text appears in the central circles with the images alternating from left to right. |


---

### ArrowRibbon {#ArrowRibbon}
| ArrowRibbon| 6 | Use to show either related or contrasting concepts with some connection, such as opposing forces. The first two lines of Level 1 text are used for text in the arrows. Unused text does not appear, but remains available if you switch layouts. |


---

### AscendingPictureAccentProcess {#AscendingPictureAccentProcess}
| AscendingPictureAccentProcess| 7 | Use to show an ascending series of pictures with descriptive text. Works best with a small amount of text. |


---

### Balance {#Balance}
| Balance| 8 | Use to compare or show the relationship between two ideas. Each of the first two lines of Level 1 text corresponds to text at the top of one side of the center point. Emphasizes Level 2 text, which is limited to four shapes on each side of the center point. The balance tips towards the side with the most shapes containing Level 2 text. Unused text does not appear, but remains available if you switch layouts. |


---

### BasicBendingProcess {#BasicBendingProcess}
| BasicBendingProcess| 9 | Use to show a progression or sequential steps in a task, process, or workflow. Maximizes both horizontal and vertical display space for shapes. |


---

### BasicBlockList {#BasicBlockList}
| BasicBlockList| 10 | Use to show non-sequential or grouped blocks of information. Maximizes both horizontal and vertical display space for shapes. |


---

### BasicChevronProcess {#BasicChevronProcess}
| BasicChevronProcess| 11 | Use to show a progression; a timeline; sequential steps in a task, process, or workflow; or to emphasize movement or direction. Level 1 text appears inside an arrow shape while Level 2 text appears below the arrow shapes. |


---

### BasicCycle {#BasicCycle}
| BasicCycle| 12 | Use to represent a continuing sequence of stages, tasks, or events in a circular flow. Emphasizes the stages or steps rather than the connecting arrows or flow. Works best with Level 1 text only. |


---

### BasicMatrix {#BasicMatrix}
| BasicMatrix| 13 | Use to show the relationship of components to a whole in quadrants. The first four lines of Level 1 text appear in the quadrants. Unused text does not appear, but remains available if you switch layouts. |


---

### BasicPie {#BasicPie}
| BasicPie| 14 | Use to show how individual parts form a whole. The first seven lines of Level 1 text correspond to the evenly distributed wedge or pie shapes. The top Level 1 text shape appears outside of the rest of the pie for emphasis. Unused text does not appear, but remains available if you switch layouts. |


---

### BasicProcess {#BasicProcess}
| BasicProcess| 15 | Use to show a progression or sequential steps in a task, process, or workflow. |


---

### BasicPyramid {#BasicPyramid}
| BasicPyramid| 16 | Use to show proportional, interconnected, or hierarchical relationships with the largest component on the bottom and narrowing up. Level 1 text appears in the pyramid segments and Level 2 text appears in shapes alongside each segment. |


---

### BasicRadial {#BasicRadial}
| BasicRadial| 17 | Use to show the relationship to a central idea in a cycle. The first line of Level 1 text corresponds to the central shape, and its Level 2 text corresponds to the surrounding circular shapes. Unused text does not appear, but remains available if you switch layouts. |


---

### BasicTarget {#BasicTarget}
| BasicTarget| 18 | Use to show containment, gradations, or hierarchical relationships. The first five lines of Level 1 text are associated with a circle. Unused text does not appear, but remains available if you switch layouts. |


---

### BasicTimeline {#BasicTimeline}
| BasicTimeline| 19 | Use to show sequential steps in a task, process, or workflow, or to show timeline information. Works well with both Level 1 and Level 2 text. |


---

### BasicVenn {#BasicVenn}
| BasicVenn| 20 | Use to show overlapping or interconnected relationships. The first seven lines of Level 1 text correspond with a circle. If there are four or fewer lines of Level 1 text, the text is inside the circles. If there are more than four lines of Level 1 text, the text is outside of the circles. Unused text does not appear, but remains available if you switch layouts. |


---

### BendingPictureAccentList {#BendingPictureAccentList}
| BendingPictureAccentList| 21 | Use to show non-sequential or grouped blocks of information. The small circular shapes are designed to contain pictures. Works well for illustrating both Level 1 and Level 2 text. Maximizes both horizontal and vertical display space for shapes. |


---

### BendingPictureBlocks {#BendingPictureBlocks}
| BendingPictureBlocks| 22 | Use to show a series of pictures. The box covering the bottom corner can contain small amounts of text. |


---

### BendingPictureCaption {#BendingPictureCaption}
| BendingPictureCaption| 23 | Use to show a sequential series of pictures. The box covering the bottom corner can contain small amounts of text. |


---

### BendingPictureCaptionList {#BendingPictureCaptionList}
| BendingPictureCaptionList| 24 | Use to show a series of pictures. The title and description appear in a callout shape under each picture. |


---

### BendingPictureSemiTransparentText {#BendingPictureSemiTransparentText}
| BendingPictureSemiTransparentText| 25 | Use to show a series of pictures. A semi-transparent box covers the lower portion of the picture and contains all levels of text. |


---

### BlockCycle {#BlockCycle}
| BlockCycle| 26 | Use to represent a continuing sequence of stages, tasks, or events in a circular flow. Emphasizes the stages or steps rather than the connecting arrows or flow. |


---

### BubblePictureList {#BubblePictureList}
| BubblePictureList| 27 | Use to show a series of pictures. Can contain up to eight Level 1 pictures. Unused text and pictures do not appear, but remain available if you switch layouts. Works best with small amounts of text. |


---

### CaptionedPictures {#CaptionedPictures}
| CaptionedPictures| 28 | Use to show pictures with multiple levels of text. Works best with a small amount of Level 1 text and a medium amount of Level 2 text. |


---

### ChevronList {#ChevronList}
| ChevronList| 29 | Use to show a progression through several processes that make up an overall workflow. Also works for illustrating contrasting processes. The Level 1 text corresponds to the first arrow shape on the left, while the Level 2 text corresponds to horizontal sub-steps for each shape that contains Level 1 text. |


---

### CircleAccentTimeline {#CircleAccentTimeline}
| CircleAccentTimeline| 30 | Use to show a series of events or timeline information. Level 1 text appears next to larger circular shapes. Level 2 text appears next to smaller circular shapes. |


---

### CircleArrowProcess {#CircleArrowProcess}
| CircleArrowProcess| 31 | Use to show sequential items with supporting text for each item. This diagram works best with small amounts of Level 1 text. |


---

### CirclePictureHierarchy {#CirclePictureHierarchy}
| CirclePictureHierarchy| 32 | Use to show hierarchical information or reporting relationships in an organization. Pictures appear in circles and corresponding text appears next to the pictures. |


---

### CircleRelationship {#CircleRelationship}
| CircleRelationship| 33 | Use to show the relationship to or from a central idea. Level 2 text is added non-sequentially and is limited to five items. There can only be one Level 1 item. |


---

### CircularBendingProcess {#CircularBendingProcess}
| CircularBendingProcess| 34 | Use to show a long or non-linear sequence or steps in a task, process, or workflow. Works best with Level 1 text only. Maximizes both horizontal and vertical display space for shapes. |


---

### CircularPictureCallout {#CircularPictureCallout}
| CircularPictureCallout| 35 | Use to show a central idea and sub-ideas or related items. The text for the first picture covers the lower portion of the picture. The corresponding text for other Level 1 shapes appears next to the small circular pictures. This diagram also works well with no text. |


---

### ClosedChevronProcess {#ClosedChevronProcess}
| ClosedChevronProcess| 36 | Use to show a progression, a timeline, or sequential steps in a task, process, or workflow, or to emphasize movement or direction. Can be used to emphasize information in the starting shape. Works best with Level 1 text only. |


---

### ContinuousArrowProcess {#ContinuousArrowProcess}
| ContinuousArrowProcess| 37 | Use to show a timeline or sequential steps in a task, process, or workflow. Works best with Level 1 text because each line of Level 1 text appears inside the arrow shape. Level 2 text appears outside the arrow shape. |


---

### ContinuousBlockProcess {#ContinuousBlockProcess}
| ContinuousBlockProcess| 38 | Use to show a progression or sequential steps in a task, process, or workflow. Works best with minimal Level 1 and Level 2 text. |


---

### ContinuousCycle {#ContinuousCycle}
| ContinuousCycle| 39 | Use to represent a continuing sequence of stages, tasks, or events in a circular flow. Emphasizes the connection between all components. Works best with Level 1 text only. |


---

### ContinuousPictureList {#ContinuousPictureList}
| ContinuousPictureList| 40 | Use to show groups of interconnected information. The circular shapes are designed to contain pictures. |


---

### ConvergingArrows {#ConvergingArrows}
| ConvergingArrows| 41 | Use to show ideas or concepts that converge to a central point. Works best with Level 1 text only. |


---

### ConvergingRadial {#ConvergingRadial}
| ConvergingRadial| 42 | Use to show relationships of concepts or components to a central idea in a cycle. The first line of Level 1 text corresponds to the central circular shape and the lines of Level 2 text correspond to the surrounding rectangular shapes. Unused text does not appear, but remains available if you switch layouts. |


---

### CounterbalanceArrows {#CounterbalanceArrows}
| CounterbalanceArrows| 43 | Use to show two opposing ideas or concepts. Each of the first two lines of Level 1 text corresponds to an arrow and works well with Level 2 text. Unused text does not appear, but remains available if you switch layouts. |


---

### CycleMatrix {#CycleMatrix}
| CycleMatrix| 44 | Use to show the relationship to a central idea in a cyclical progression. Each of the first four lines of Level 1 text corresponds to a wedge or pie shape, and Level 2 text appears in a rectangular shape to the side of the wedge or pie shape. Unused text does not appear, but remains available if you switch layouts. |


---

### DescendingBlockList {#DescendingBlockList}
| DescendingBlockList| 45 | Use to show groups of related ideas or lists of information. The text shapes decrease in height sequentially, and the Level 1 text displays vertically. |


---

### DescendingProcess {#DescendingProcess}
| DescendingProcess| 46 | Use to show a descending series of events. The first Level 1 text is at the top of arrow, and the last Level 1 text displays at the bottom of the arrow. Only the first seven Level 1 items appear. Works best with small to medium amounts of text. |


---

### DetailedProcess {#DetailedProcess}
| DetailedProcess| 47 | Use with large amounts of Level 2 text to show a progression through stages. |


---

### DivergingArrows {#DivergingArrows}
| DivergingArrows| 48 | Use to show ideas or concepts that progress outward from a central source. Works best with Level 1 text only. |


---

### DivergingRadial {#DivergingRadial}
| DivergingRadial| 49 | Use to show relationships to a central idea in a cycle. The first Level 1 line of text corresponds to the central circular shape. Emphasizes the surrounding circles rather than the central idea. Unused text does not appear, but remains available if you switch layouts. |


---

### Equation {#Equation}
| Equation| 50 | Use to show sequential steps or tasks that depict a plan or result. The last Level 1 line of text appears after the equals sign (=).Works best with Level 1 text only. |


---

### FramedTextPicture {#FramedTextPicture}
| FramedTextPicture| 51 | Use to show pictures with corresponding Level 1 text displayed in a frame. |


---

### Funnel {#Funnel}
| Funnel| 52 | Use to show the filtering of information or how parts merge into a whole. Emphasizes the final outcome. Can contain up to four lines of Level 1 text; the last of these four Level 1 text lines appears below the funnel and the other lines correspond to a circular shape. Unused text does not appear, but remains available if you switch layouts. |


---

### Gear {#Gear}
| Gear| 53 | Use to show interlocking ideas. Each of the first three lines of Level 1 text corresponds to a gear shape, and their corresponding Level 2 text appears in rectangles next to the gear shape. Unused text does not appear, but remains available if you switch layouts. |


---

### GridMatrix {#GridMatrix}
| GridMatrix| 54 | Use to show the placement of concepts along two axes. Emphasizes the individual components rather than the whole. The first four lines of Level 1 text appear in the quadrants. Unused text does not appear, but remains available if you switch layouts. |


---

### GroupedList {#GroupedList}
| GroupedList| 55 | Use to show groups and sub-groups of information, or steps and sub-steps in a task, process, or workflow. Level 1 text corresponds to the top level horizontal shapes, and Level 2 text corresponds to vertical sub-steps under each related top level shape. Works well for emphasizing sub-groups or sub-steps, hierarchical information, or multiple lists of information. |


---

### HalfCircleOrganizationChart {#HalfCircleOrganizationChart}
| HalfCircleOrganizationChart| 56 | Use to show hierarchical information or reporting relationships in an organization. The assistant shapes and Org Chart hanging layouts are available with this layout. |


---

### HexagonCluster {#HexagonCluster}
| HexagonCluster| 57 | Use to show pictures with associated descriptive text. Small hexagons indicate the picture and text pair. Works best with small amounts of text. |


---

### Hierarchy {#Hierarchy}
| Hierarchy| 58 | Use to show hierarchical relationships progressing from top to bottom. |


---

### HierarchyList {#HierarchyList}
| HierarchyList| 59 | Use to show hierarchical relationships progressing across groups. Can also be used to group or list information. |


---

### HorizontalBulletList {#HorizontalBulletList}
| HorizontalBulletList| 60 | Use to show non-sequential or grouped lists of information. Works well with large amounts of text. All text has the same level of emphasis, and direction is not implied. |


---

### HorizontalHierarchy {#HorizontalHierarchy}
| HorizontalHierarchy| 61 | Use to show hierarchical relationships progressing horizontally. Works well for decision trees. |


---

### HorizontalLabeledHierarchy {#HorizontalLabeledHierarchy}
| HorizontalLabeledHierarchy| 62 | Use to show hierarchical relationships progressing horizontally and grouped hierarchically. Emphasizes heading or level 1 text. The first line of Level 1 text appears in the shape at the beginning of the hierarchy, and the second and all subsequent lines of Level 1 text appear at the top of the tall rectangles. |


---

### HorizontalMultiLevelHierarchy {#HorizontalMultiLevelHierarchy}
| HorizontalMultiLevelHierarchy| 63 | Use to show large amounts of hierarchical information progressing horizontally. The top of the hierarchy is displayed vertically. This layout supports many levels in the hierarchy. |


---

### HorizontalOrganizationChart {#HorizontalOrganizationChart}
| HorizontalOrganizationChart| 64 | Use to show hierarchical information horizontally or reporting relationships in an organization. The assistant shape and the Org Chart hanging layouts are available with this layout. |


---

### HorizontalPictureList {#HorizontalPictureList}
| HorizontalPictureList| 65 | Use to show non-sequential or grouped information with an emphasis on related pictures. The top shapes are designed to contain pictures. |


---

### IncreasingArrowsProcess {#IncreasingArrowsProcess}
| IncreasingArrowsProcess| 66 | Use to show sequential and overlapping steps in a process. Limited to five Level 1 items. Level 2 can contain large amounts of text. |


---

### IncreasingCircleProcess {#IncreasingCircleProcess}
| IncreasingCircleProcess| 67 | Use to show a series of steps, with the interior of the circle increasing with each step. Limited to seven Level 1 steps but unlimited Level 2 items. Works well with large amounts of Level 2 text. |


---

### InvertedPyramid {#InvertedPyramid}
| InvertedPyramid| 68 | Use to show proportional, interconnected, or hierarchical relationships with the largest component on the top and narrowing down. Level 1 text appears in the pyramid segments and Level 2 text appears in shapes alongside each segment. |


---

### LabeledHierarchy {#LabeledHierarchy}
| LabeledHierarchy| 69 | Use to show hierarchical relationships progressing from top to bottom and grouped hierarchically. Emphasizes heading or level 1 text. The first line of Level 1 text appears in the shape at the beginning of the hierarchy, and all subsequent lines of Level 1 text appear to the left of the long rectangles. |


---

### LinearVenn {#LinearVenn}
| LinearVenn| 70 | Use to show overlapping relationships in a sequence. Works best with Level 1 text only. |


---

### LinedList {#LinedList}
| LinedList| 71 | Use to show large amounts of text divided into categories and subcategories. Works well with multiple levels of text. Text at the same level is separated by lines. |


---

### MultidirectionalCycle {#MultidirectionalCycle}
| MultidirectionalCycle| 72 | Use to represent a continuing sequence of stages, tasks, or events that can occur in any direction. |


---

### NameandTitleOrganizationChart {#NameandTitleOrganizationChart}
| NameandTitleOrganizationChart| 73 | Use to show hierarchical information or reporting relationships in an organization. To enter text in the title box, type directly in the smaller rectangular shape. The assistant shape and Org Chart hanging layouts are available with this layout. |


---

### NestedTarget {#NestedTarget}
| NestedTarget| 74 | Use to show containment relationships. Each of the first three lines of Level 1 text correspond to the upper left text in the shapes, and Level 2 text corresponds to the smaller shapes. Works best with minimal Level 2 lines of text. Unused text does not appear, but remains available if you switch layouts. |


---

### NondirectionalCycle {#NondirectionalCycle}
| NondirectionalCycle| 75 | Use to represent a continuing sequence of stages, tasks, or events in a circular flow. Each shape has the same level of importance. Works well when direction does not need to be indicated. |


---

### OpposingArrows {#OpposingArrows}
| OpposingArrows| 76 | Use to show two opposing ideas, or ideas that diverge from a central point. Each of the first two lines of Level 1 text corresponds to an arrow. Unused text does not appear, but remains available if you switch layouts. |


---

### OpposingIdeas {#OpposingIdeas}
| OpposingIdeas| 77 | Use to show two opposing or contrasting ideas. Can have one or two Level 1 items. Each Level 1 text can contain multiple sub-levels. Works well with large amounts of text. |


---

### OrganizationChart {#OrganizationChart}
| OrganizationChart| 78 | Use to show hierarchical information or reporting relationships in an organization. The assistant shape and the Org Chart hanging layouts are available with this layout. |


---

### PhasedProcess {#PhasedProcess}
| PhasedProcess| 79 | Use to show three phases of a process. Limited to three Level 1 items. The first two Level 1 items can each contain four Level 2 items, and the third Level 1 item can contain an unlimited number of Level 2 items. Works best with small amounts of text. |


---

### PictureAccentBlocks {#PictureAccentBlocks}
| PictureAccentBlocks| 80 | Use to show a group of pictures in blocks starting from the corner. The corresponding text displays vertically. Works well as an accent on title or sub-title slides or for section breaks of a document. |


---

### PictureAccentList {#PictureAccentList}
| PictureAccentList| 81 | Use to show grouped or related information. The small shapes on the upper corners are designed to contain pictures. Emphasizes Level 2 text over Level 1 text, and is a good choice for large amounts of Level 2 text. |


---

### PictureAccentProcess {#PictureAccentProcess}
| PictureAccentProcess| 82 | Use to show sequential steps in a task, process, or workflow. The rectangular shapes in the background are designed to contain pictures. |


---

### PictureCaptionList {#PictureCaptionList}
| PictureCaptionList| 83 | Use to show non-sequential or grouped blocks of information. The top shapes are designed to contain pictures and pictures are emphasized over text. Works well for pictures with short text captions. |


---

### PictureGrid {#PictureGrid}
| PictureGrid| 84 | Use to show pictures laid out on a square grid. Best with a small amount of Level 1 text, which appears above the picture. |


---

### PictureLineup {#PictureLineup}
| PictureLineup| 85 | Use to show a series of pictures side by side. Level 1 text covers the top of the picture. Level 2 text appears below the picture. |


---

### PictureStrips {#PictureStrips}
| PictureStrips| 86 | Use to show a series of pictures from top to bottom with Level 1 text beside each. |


---

### PieProcess {#PieProcess}
| PieProcess| 87 | Use to show steps in a process with each pie slice increasing in size up to seven shapes. Level 1 text displays vertically. |


---

### PlusandMinus {#PlusandMinus}
| PlusandMinus| 88 | Use to show the pros and cons of two ideas. Each Level 1 text can contain multiple sub-levels. Works well with large amounts of text. Limited to two Level 1 items. |


---

### ProcessArrows {#ProcessArrows}
| ProcessArrows| 89 | Use to show information illustrating a process or workflow. Level 1 text appears in the circular shapes and Level 2 text appears in the arrow shapes. Works best for minimal text and to emphasize movement or direction. |


---

### ProcessList {#ProcessList}
| ProcessList| 90 | Use to show multiple groups of information or steps and sub-steps in a task, process, or workflow. Level 1 text corresponds to the top horizontal shapes, and Level 2 text corresponds to vertical sub-steps under each related top level shape. |


---

### PyramidList {#PyramidList}
| PyramidList| 91 | Use to show proportional, interconnected, or hierarchical relationships. Text appears in the rectangular shapes on top of the pyramid background. |


---

### RadialCluster {#RadialCluster}
| RadialCluster| 92 | Use to show data that relates to a central idea or theme. The top Level 1 text appears in the center. Level 2 text appears in surrounding shapes. Can contain up to seven Level 2 shapes. Unused text does not appear, but remains available if you switch layouts. Works best with small amounts of text. |


---

### RadialCycle {#RadialCycle}
| RadialCycle| 93 | Use to show the relationship to a central idea. Emphasizes both information in the center circle and how information in the outer ring of circles contributes to the central idea. The first Level 1 line of text corresponds to the central circle, and its Level 2 text corresponds to the outer ring of circles. Unused text does not appear, but remains available if you switch layouts. |


---

### RadialList {#RadialList}
| RadialList| 94 | Use to show relationships to a central idea in a cycle. The center shape can contain a picture. Level 1 text appears in the smaller circles and any related Level 2 text appears to the side of the smaller circles. |


---

### RadialVenn {#RadialVenn}
| RadialVenn| 95 | Use to show both overlapping relationships and the relationship to a central idea in a cycle. The first line of Level 1 text corresponds to the central shape and the lines of Level 2 text correspond to the surrounding circular shapes. Unused text does not appear, but remains available if you switch layouts. |


---

### RandomToResultProcess {#RandomToResultProcess}
| RandomToResultProcess| 96 | Use to show, through a series of steps, how several chaotic ideas can result in a unified goal or idea. Supports multiple items of Level 1 text, but the first and last Level 1 corresponding shapes are fixed. Works best with small amounts of Level 1 text and medium amounts of Level 2 text. |


---

### RepeatingBendingProcess {#RepeatingBendingProcess}
| RepeatingBendingProcess| 97 | Use to show a progression or sequential steps in a task, process, or workflow. Maximizes both horizontal and vertical display space for shapes. |


---

### ReverseList {#ReverseList}
| ReverseList| 98 | Use to change between two items. Only the first two items of text display, and each item can contain a large amount of text. Works well to show a change between two items or shift in order. |


---

### SegmentedCycle {#SegmentedCycle}
| SegmentedCycle| 99 | Use to show a progression or a sequence of stages, tasks, or events in a circular flow. Emphasizes the interconnected pieces. Each of the first seven lines of Level 1 text corresponds to a wedge or pie shape. Unused text does not appear, but remains available if you switch layouts. |


---

### SegmentedProcess {#SegmentedProcess}
| SegmentedProcess| 100 | Use to show a progression or sequential steps in a task, process, or workflow. Emphasizes Level 2 text, since each line appears in a separate shape. |


---

### SegmentedPyramid {#SegmentedPyramid}
| SegmentedPyramid| 101 | Use to show containment, proportional, or interconnected relationships. The first nine lines of Level 1 text appear in the triangular shapes. Unused text does not appear, but remains available if you switch layouts. Works best with Level 1 text only. |


---

### SnapshotPictureList {#SnapshotPictureList}
| SnapshotPictureList| 102 | Use to show pictures with explanatory text. Level 2 text can display lists of information. Works well with a large amount of text. |


---

### SpiralPicture {#SpiralPicture}
| SpiralPicture| 103 | Use to show a series of up to five pictures with corresponding Level 1 captions that spiral in to the center. |


---

### SquareAccentList {#SquareAccentList}
| SquareAccentList| 104 | Use to show lists of information divided into categories. Level 2 text appears beside a small square shape. Works well with large amounts of Level 2 text. |


---

### StackedList {#StackedList}
| StackedList| 105 | Use to show groups of information or steps in a task, process, or workflow. Circular shapes contain Level 1 text, and the corresponding rectangles contain Level 2 text. Works well for numerous details and minimal Level 1 text. |


---

### StackedVenn {#StackedVenn}
| StackedVenn| 106 | Use to show overlapping relationships. A good choice for emphasizing growth or gradation. Works best with Level 1 text only. The first seven lines of Level 1 text correspond to a circular shape. Unused text does not appear, but remains available if you switch layouts. |


---

### StaggeredProcess {#StaggeredProcess}
| StaggeredProcess| 107 | Use to show a downward progression through stages. Each of the first five lines of Level 1 text corresponds with a rectangle. Unused text does not appear, but remains available if you switch layouts. |


---

### StepDownProcess {#StepDownProcess}
| StepDownProcess| 108 | Use to show a descending process with multiple steps and sub-steps. Works best with small amounts of text. |


---

### StepUpProcess {#StepUpProcess}
| StepUpProcess| 109 | Use to show an ascending series of steps or lists of information. |


---

### SubStepProcess {#SubStepProcess}
| SubStepProcess| 110 | Use to show a multi-step process with sub-steps between each instance of Level 1 text. Works best with small amounts of text and is limited to seven Level 1 steps. Each Level 1 step can have unlimited sub-steps. |


---

### TableHierarchy {#TableHierarchy}
| TableHierarchy| 111 | Use to show groups of information built from top to bottom, and the hierarchies within each group. This layout does not contain connecting lines. |


---

### TableList {#TableList}
| TableList| 112 | Use to show grouped or related information of equal value. The first Level 1 line of text corresponds to the top shape and its Level 2 text is used for the subsequent lists. |


---

### TargetList {#TargetList}
| TargetList| 113 | Use to show interrelated or overlapping information. Each of the first seven lines of Level 1 text appears in the rectangular shape. Unused text does not appear, but remains available if you switch layouts. Works well with both Level 1 and Level 2 text. |


---

### TextCycle {#TextCycle}
| TextCycle| 114 | Use to represent a continuing sequence of stages, tasks, or events in a circular flow. Emphasizes the arrows or flow rather than the stages or steps. Works best with Level 1 text only. |


---

### TitlePictureLineup {#TitlePictureLineup}
| TitlePictureLineup| 115 | Use to show a series of pictures that each have their own title and description. Level 1 text appears in the box above the picture. Level 2 text appears below the picture. |


---

### TitledMatrix {#TitledMatrix}
| TitledMatrix| 116 | Use to show the relationships of four quadrants to a whole. The first line of Level 1 text corresponds to the central shape, and the first four lines of Level 2 text appear in the quadrants. Unused text does not appear, but remains available if you switch layouts. |


---

### TitledPictureAccentList {#TitledPictureAccentList}
| TitledPictureAccentList| 117 | Use to show lists of information with an accent picture for each Level 2 text. Level 1 text displays in a separate box at the top of the list. |


---

### TitledPictureBlocks {#TitledPictureBlocks}
| TitledPictureBlocks| 118 | Use to show a series of pictures. Level 1 text appears above each picture. Level 2 text appears to the side and slightly overlapping each picture. |


---

### TrapezoidList {#TrapezoidList}
| TrapezoidList| 119 | Use to show grouped or related information of equal value. Works well with large amounts of text. |


---

### UpwardArrow {#UpwardArrow}
| UpwardArrow| 120 | Use to show a progression or steps that trend upward in a task, process, or workflow. Each of the first five lines of Level 1 text corresponds to a point on the arrow. Works best with minimal text. Unused text does not appear, but remains available if you switch layouts. |


---

### VerticalAccentList {#VerticalAccentList}
| VerticalAccentList| 121 | Use to show lists of information. Level 2 text appears in rectangular shapes over vertical chevrons. Emphasizes Level 2 text over Level 1 text, and is a good choice for medium amounts of Level 2 text. |


---

### VerticalArrowList {#VerticalArrowList}
| VerticalArrowList| 122 | Use to show a progression or sequential steps in a task, process, or workflow that move toward a common goal. Works well for bulleted lists of information. |


---

### VerticalBendingProcess {#VerticalBendingProcess}
| VerticalBendingProcess| 123 | Use to show a progression or sequential steps in a task, process, or workflow. Maximizes both horizontal and vertical display space for shapes. Places more emphasis on the interrelationships among the shapes than on direction or movement. |


---

### VerticalBlockList {#VerticalBlockList}
| VerticalBlockList| 124 | Use to show groups of information or steps in a task, process, or workflow. Works well with large amounts of Level 2 text. A good choice for text with a main point and multiple sub-points. |


---

### VerticalBoxList {#VerticalBoxList}
| VerticalBoxList| 125 | Use to show several groups of information, especially groups with large amounts of Level 2 text. A good choice for bulleted lists of information. |


---

### VerticalBulletList {#VerticalBulletList}
| VerticalBulletList| 126 | Use to show non-sequential or grouped blocks of information. Works well for lists with long headings or top level information. |


---

### VerticalChevronList {#VerticalChevronList}
| VerticalChevronList| 127 | Use to show a progression or sequential steps in a task, process, or workflow, or to emphasize movement or direction. Emphasizes Level 2 text over Level 1 text, and is a good choice for large amounts of Level 2 text. |


---

### VerticalCircleList {#VerticalCircleList}
| VerticalCircleList| 128 | Use to show sequential or grouped data. Works best for Level 1 text, which displays next to a large circular shape. Lower levels of text are separated with smaller circular shapes. |


---

### VerticalCurvedList {#VerticalCurvedList}
| VerticalCurvedList| 129 | Use to show a curved list of information. To add pictures to the accent circle shapes, apply a picture fill. |


---

### VerticalEquation {#VerticalEquation}
| VerticalEquation| 130 | Use to show sequential steps or tasks that depict a plan or result. The last Level 1 line of text appears after the arrow. Works best with Level 1 text only. |


---

### VerticalPictureAccentList {#VerticalPictureAccentList}
| VerticalPictureAccentList| 131 | Use to show non-sequential or grouped blocks of information. The small circles are designed to contain pictures. |


---

### VerticalPictureList {#VerticalPictureList}
| VerticalPictureList| 132 | Use to show non-sequential or grouped blocks of information. The small shapes on the left are designed to contain pictures. |


---

### VerticalProcess {#VerticalProcess}
| VerticalProcess| 133 | Use to show a progression or sequential steps in a task, process, or workflow from top to bottom. Works best with Level 1 text, since the vertical space is limited. |


---

### Custom {#Custom}
| Custom| 134 | Represents a SmartArt diagram with custom layout template |


---

### PictureOrganizationChart {#PictureOrganizationChart}
| PictureOrganizationChart| 135 | Use to show hierarchical information or reporting relationships in an organization, with corresponding pictures. The assistant shape and Org Chart hanging layouts are available with this layout. |


---


