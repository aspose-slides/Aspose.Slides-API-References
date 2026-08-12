---
title: SmartArtLayoutType
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แสดงประเภทการจัดวางของแผนภาพ SmartArt
type: docs
weight: 157
url: /th/aspose.slides.smartart/smartartlayouttype/
---
## SmartArtLayoutType enum

แสดงประเภทเค้าโครงของแผนภาพ [SmartArt](../smartart/).

```cpp
enum class SmartArtLayoutType
```

### Values

| ชื่อ | ค่า | คำอธิบาย |
| --- | --- | --- |
| AccentProcess | 0 | Use to show a progression, a timeline, or sequential steps in a task, process, or workflow. Works well for illustrating both Level 1 and Level 2 text. |
| AccentedPicture | 1 | Use to show a central, photographic idea with related ideas on the side. The top Level 1 text appears over the central picture. Corresponding text for other Level 1 shapes appear next to the small circular pictures. This layout also works well with no text. |
| AlternatingFlow | 2 | Use to show groups of information or sequential steps in a task, process, or workflow. Emphasizes the interaction or relationships among the groups of information. |
| AlternatingHexagons | 3 | Use to represent a series of interconnected ideas. Level 1 text appears inside the hexagons. Level 2 text appears outside the shapes. |
| AlternatingPictureBlocks | 4 | Use to show a series of pictures from top to bottom. Text appears alternately on the right or left of the picture. |
| AlternatingPictureCircles | 5 | Use to show a set of pictures with text. The corresponding text appears in the central circles with the images alternating from left to right. |
| ArrowRibbon | 6 | Use to show either related or contrasting concepts with some connection, such as opposing forces. The first two lines of Level 1 text are used for text in the arrows. Unused text does not appear, but remains available if you switch layouts. |
| AscendingPictureAccentProcess | 7 | Use to show an ascending series of pictures with descriptive text. Works best with a small amount of text. |
| Balance | 8 | Use to compare or show the relationship between two ideas. Each of the first two lines of Level 1 text corresponds to text at the top of one side of the center point. Emphasizes Level 2 text, which is limited to four shapes on each side of the center point. The balance tips towards the side with the most shapes containing Level 2 text. Unused text does not appear, but remains available if you switch layouts. |
| BasicBendingProcess | 9 | Use to show a progression or sequential steps in a task, process, or workflow. Maximizes both horizontal and vertical display space for shapes. |
| BasicBlockList | 10 | Use to show non-sequential or grouped blocks of information. Maximizes both horizontal and vertical display space for shapes. |
| BasicChevronProcess | 11 | Use to show a progression; a timeline; sequential steps in a task, process, or workflow; or to emphasize movement or direction. Level 1 text appears inside an arrow shape while Level 2 text appears below the arrow shapes. |
| BasicCycle | 12 | Use to represent a continuing sequence of stages, tasks, or events in a circular flow. Emphasizes the stages or steps rather than the connecting arrows or flow. Works best with Level 1 text only. |
| BasicMatrix | 13 | Use to show the relationship of components to a whole in quadrants. The first four lines of Level 1 text appear in the quadrants. Unused text does not appear, but remains available if you switch layouts. |
| BasicPie | 14 | Use to show how individual parts form a whole. The first seven lines of Level 1 text correspond to the evenly distributed wedge or pie shapes. The top Level 1 text shape appears outside of the rest of the pie for emphasis. Unused text does not appear, but remains available if you switch layouts. |
| BasicProcess | 15 | Use to show a progression or sequential steps in a task, process, or workflow. |
| BasicPyramid | 16 | Use to show proportional, interconnected, or hierarchical relationships with the largest component on the bottom and narrowing up. Level 1 text appears in the pyramid segments and Level 2 text appears in shapes alongside each segment. |
| BasicRadial | 17 | Use to show the relationship to a central idea in a cycle. The first line of Level 1 text corresponds to the central shape, and its Level 2 text corresponds to the surrounding circular shapes. Unused text does not appear, but remains available if you switch layouts. |
| BasicTarget | 18 | Use to show containment, gradations, or hierarchical relationships. The first five lines of Level 1 text are associated with a circle. Unused text does not appear, but remains available if you switch layouts. |
| BasicTimeline | 19 | Use to show sequential steps in a task, process, or workflow, or to show timeline information. Works well with both Level 1 and Level 2 text. |
| BasicVenn | 20 | Use to show overlapping or interconnected relationships. The first seven lines of Level 1 text correspond with a circle. If there are four or fewer lines of Level 1 text, the text is inside the circles. If there are more than four lines of Level 1 text, the text is outside of the circles. Unused text does not appear, but remains available if you switch layouts. |
| BendingPictureAccentList | 21 | Use to show non-sequential or grouped blocks of information. The small circular shapes are designed to contain pictures. Works well for illustrating both Level 1 and Level 2 text. Maximizes both horizontal and vertical display space for shapes. |
| BendingPictureBlocks | 22 | Use to show a series of pictures. The box covering the bottom corner can contain small amounts of text. |
| BendingPictureCaption | 23 | Use to show a sequential series of pictures. The box covering the bottom corner can contain small amounts of text. |
| BendingPictureCaptionList | 24 | Use to show a series of pictures. The title and description appear in a callout shape under each picture. |
| BendingPictureSemiTransparentText | 25 | Use to show a series of pictures. A semi-transparent box covers the lower portion of the picture and contains all levels of text. |
| BlockCycle | 26 | Use to represent a continuing sequence of stages, tasks, or events in a circular flow. Emphasizes the stages or steps rather than the connecting arrows or flow. |
| BubblePictureList | 27 | Use to show a series of pictures. Can contain up to eight Level 1 pictures. Unused text and pictures do not appear, but remain available if you switch layouts. Works best with small amounts of text. |
| CaptionedPictures | 28 | Use to show pictures with multiple levels of text. Works best with a small amount of Level 1 text and a medium amount of Level 2 text. |
| ChevronList | 29 | Use to show a progression through several processes that make up an overall workflow. Also works for illustrating contrasting processes. The Level 1 text corresponds to the first arrow shape on the left, while the Level 2 text corresponds to horizontal sub-steps for each shape that contains Level 1 text. |
| CircleAccentTimeline | 30 | Use to show a series of events or timeline information. Level 1 text appears next to larger circular shapes. Level 2 text appears next to smaller circular shapes. |
| CircleArrowProcess | 31 | Use to show sequential items with supporting text for each item. This diagram works best with small amounts of Level 1 text. |
| CirclePictureHierarchy | 32 | Use to show hierarchical information or reporting relationships in an organization. Pictures appear in circles and corresponding text appears next to the pictures. |
| CircleRelationship | 33 | Use to show the relationship to or from a central idea. Level 2 text is added non-sequentially and is limited to five items. There can only be one Level 1 item. |
| CircularBendingProcess | 34 | Use to show a long or non-linear sequence or steps in a task, process, or workflow. Works best with Level 1 text only. Maximizes both horizontal and vertical display space for shapes. |
| CircularPictureCallout | 35 | Use to show a central idea and sub-ideas or related items. The text for the first picture covers the lower portion of the picture. The corresponding text for other Level 1 shapes appears next to the small circular pictures. This diagram also works well with no text. |
| ClosedChevronProcess | 36 | Use to show a progression, a timeline, or sequential steps in a task, process, or workflow, or to emphasize movement or direction. Can be used to emphasize information in the starting shape. Works best with Level 1 text only. |
| ContinuousArrowProcess | 37 | Use to show a timeline or sequential steps in a task, process, or workflow. Works best with Level 1 text because each line of Level 1 text appears inside the arrow shape. Level 2 text appears outside the arrow shape. |
| ContinuousBlockProcess | 38 | Use to show a progression or sequential steps in a task, process, or workflow. Works best with minimal Level 1 and Level 2 text. |
| ContinuousCycle | 39 | Use to represent a continuing sequence of stages, tasks, or events in a circular flow. Emphasizes the connection between all components. Works best with Level 1 text only. |
| ContinuousPictureList | 40 | Use to show groups of interconnected information. The circular shapes are designed to contain pictures. |
| ConvergingArrows | 41 | Use to show ideas or concepts that converge to a central point. Works best with Level 1 text only. |
| ConvergingRadial | 42 | Use to show relationships of concepts or components to a central idea in a cycle. The first line of Level 1 text corresponds to the central circular shape and the lines of Level 2 text correspond to the surrounding rectangular shapes. Unused text does not appear, but remains available if you switch layouts. |
| CounterbalanceArrows | 43 | Use to show two opposing ideas or concepts. Each of the first two lines of Level 1 text corresponds to an arrow and works well with Level 2 text. Unused text does not appear, but remains available if you switch layouts. |
| CycleMatrix | 44 | Use to show the relationship to a central idea in a cyclical progression. Each of the first four lines of Level 1 text corresponds to a wedge or pie shape, and Level 2 text appears in a rectangular shape to the side of the wedge or pie shape. Unused text does not appear, but remains available if you switch layouts. |
| DescendingBlockList | 45 | Use to show groups of related ideas or lists of information. The text shapes decrease in height sequentially, and the Level 1 text displays vertically. |
| DescendingProcess | 46 | Use to show a descending series of events. The first Level 1 text is at the top of arrow, and the last Level 1 text displays at the bottom of the arrow. Only the first seven Level 1 items appear. Works best with small to medium amounts of text. |
| DetailedProcess | 47 | Use with large amounts of Level 2 text to show a progression through stages. |
| DivergingArrows | 48 | Use to show ideas or concepts that progress outward from a central source. Works best with Level 1 text only. |
| DivergingRadial | 49 | Use to show relationships to a central idea in a cycle. The first Level 1 line of text corresponds to the central circular shape. Emphasizes the surrounding circles rather than the central idea. Unused text does not appear, but remains available if you switch layouts. |
| Equation | 50 | Use to show sequential steps or tasks that depict a plan or result. The last Level 1 line of text appears after the equals sign (=).Works best with Level 1 text only. |
| FramedTextPicture | 51 | Use to show pictures with corresponding Level 1 text displayed in a frame. |
| Funnel | 52 | Use to show the filtering of information or how parts merge into a whole. Emphasizes the final outcome. Can contain up to four lines of Level 1 text; the last of these four Level 1 text lines appears below the funnel and the other lines correspond to a circular shape. Unused text does not appear, but remains available if you switch layouts. |
| Gear | 53 | Use to show interlocking ideas. Each of the first three lines of Level 1 text corresponds to a gear shape, and their corresponding Level 2 text appears in rectangles next to the gear shape. Unused text does not appear, but remains available if you switch layouts. |
| GridMatrix | 54 | ใช้เพื่อแสดงตำแหน่งของแนวคิดตามสองแกน เน้นส่วนประกอบแต่ละส่วนมากกว่าทั้งหมด บรรทัดแรกสี่บรรทัดของข้อความระดับ 1 ปรากฏในสี่ส่วนของกริด ข้อความที่ไม่ได้ใช้จะไม่ปรากฏ แต่ยังคงพร้อมใช้งานหากคุณเปลี่ยนเค้าโครง |
| GroupedList | 55 | ใช้เพื่อแสดงกลุ่มและกลุ่มย่อยของข้อมูล หรือขั้นตอนและขั้นตอนย่อยในงาน กระบวนการ หรือโฟลว์งาน ข้อความระดับ 1 ตรงกับรูปร่างแนวนอนระดับบนสุดและข้อความระดับ 2 ตรงกับขั้นตอนย่อยแนวตั้งใต้รูปร่างระดับบนที่เกี่ยวข้อง ทำงานได้ดีเมื่อเน้นกลุ่มย่อยหรือขั้นตอนย่อย ข้อมูลเชิงลำดับขั้นหรือหลายรายการข้อมูล |
| HalfCircleOrganizationChart | 56 | ใช้เพื่อแสดงข้อมูลเชิงลำดับขั้นหรือความสัมพันธ์การรายงานในองค์กร รูปแบบผู้ช่วยและเค้าโครงผังองค์กรแบบห่ายพร้อมให้ใช้กับเค้าโครงนี้ |
| HexagonCluster | 57 | ใช้เพื่อแสดงรูปภาพพร้อมข้อความบรรยายที่เกี่ยวข้อง รูปหกเหลี่ยมขนาดเล็กบ่งบอกคู่รูปภาพและข้อความ ทำงานได้ดีที่สุดกับข้อความจำนวนเล็กน้อย |
| Hierarchy | 58 | ใช้เพื่อแสดงความสัมพันธ์เชิงลำดับขั้นที่ดำเนินจากบนลงล่าง |
| HierarchyList | 59 | ใช้เพื่อแสดงความสัมพันธ์เชิงลำดับขั้นที่ดำเนินข้ามกลุ่ม สามารถใช้เพื่อจัดกลุ่มหรือแสดงรายการข้อมูลได้เช่นกัน |
| HorizontalBulletList | 60 | ใช้เพื่อแสดงรายการข้อมูลที่ไม่เรียงลำดับหรือจัดกลุ่ม ทำงานได้ดีกับข้อความจำนวนมากข้อความทั้งหมดมีระดับความสำคัญเท่ากันและไม่ได้บ่งบอกทิศทาง |
| HorizontalHierarchy | 61 | ใช้เพื่อแสดงความสัมพันธ์เชิงลำดับขั้นที่ดำเนินในแนวนอน ทำงานได้ดีสำหรับต้นไม้การตัดสินใจ |
| HorizontalLabeledHierarchy | 62 | ใช้เพื่อแสดงความสัมพันธ์เชิงลำดับขั้นที่ดำเนินในแนวนอนและจัดกลุ่มตามลำดับขั้น เน้นหัวเรื่องหรือข้อความระดับ 1 บรรทัดแรกของข้อความระดับ 1 ปรากฏในรูปที่จุดเริ่มต้นของลำดับขั้นและบรรทัดที่สองและบรรทัดต่อ ๆ ไปของข้อความระดับ 1 ปรากฏที่ด้านบนของสี่เหลี่ยมยาว |
| HorizontalMultiLevelHierarchy | 63 | ใช้เพื่อแสดงข้อมูลเชิงลำดับขั้นจำนวนมากที่ดำเนินในแนวนอน ส่วนบนของลำดับขั้นจะแสดงในแนวดิ่ง เค้าโครงนี้รองรับหลายระดับในลำดับขั้น |
| HorizontalOrganizationChart | 64 | ใช้เพื่อแสดงข้อมูลเชิงลำดับขั้นในแนวนอนหรือความสัมพันธ์การรายงานในองค์กร รูปแบบผู้ช่วยและเค้าโครงผังองค์กรแบบห่ายพร้อมให้ใช้กับเค้าโครงนี้ |
| HorizontalPictureList | 65 | ใช้เพื่อแสดงข้อมูลที่ไม่เรียงลำดับหรือจัดกลุ่มโดยเน้นรูปภาพที่เกี่ยวข้อง รูปด้านบนออกแบบให้บรรจุรูปภาพ |
| IncreasingArrowsProcess | 66 | ใช้เพื่อแสดงขั้นตอนต่อเนื่องและทับซ้อนในกระบวนการ จำกัดที่รายการระดับ 1 จำนวนห้ารายการ ระดับ 2 สามารถบรรจุตข้อความจำนวนมาก |
| IncreasingCircleProcess | 67 | ใช้เพื่อแสดงลำดับขั้นตอนโดยภายในวงกลมขยายเพิ่มขึ้นในแต่ละขั้น จำกัดที่ขั้นระดับ 1 จำนวนเจ็ดขั้นแต่รายการระดับ 2 ไม่จำกัด ทำงานได้ดีกับข้อความระดับ 2 จำนวนมาก |
| InvertedPyramid | 68 | ใช้เพื่อแสดงความสัมพันธ์เชิงสัดส่วน เชื่อมต่อหรือเชิงลำดับขั้นโดยส่วนที่ใหญ่ที่สุดอยู่บนสุดแล้วแคบลงลงมา ข้อความระดับ 1 ปรากฏในส่วนของพีระมิดและข้อความระดับ 2 ปรากฏในรูปที่อยู่ข้างแต่ละส่วน |
| LabeledHierarchy | 69 | ใช้เพื่อแสดงความสัมพันธ์เชิงลำดับขั้นที่ดำเนินจากบนลงล่างและจัดกลุ่มตามลำดับขั้น เน้นหัวเรื่องหรือข้อความระดับ 1 บรรทัดแรกของข้อความระดับ 1 ปรากฏในรูปที่จุดเริ่มต้นของลำดับขั้นและบรรทัดต่อไปของข้อความระดับ 1 ปรากฏทางด้านซ้ายของสี่เหลี่ยมยาว |
| LinearVenn | 70 | ใช้เพื่อแสดงความสัมพันธ์ที่ทับซ้อนกันในลำดับ ทำงานได้ดีที่สุดกับข้อความระดับ 1 เท่านั้น |
| LinedList | 71 | ใช้เพื่อแสดงข้อความจำนวนมากแบ่งเป็นหมวดหมู่และหัวข้อย่อย ทำงานได้ดีกับหลายระดับของข้อความข้อความในระดับเดียวกันจะแยกด้วยเส้น |
| MultidirectionalCycle | 72 | ใช้เพื่อแสดงลำดับต่อเนื่องของขั้นตอน งาน หรือเหตุการณ์ที่สามารถเกิดขึ้นได้ในทุกทิศทาง |
| NameandTitleOrganizationChart | 73 | ใช้เพื่อแสดงข้อมูลเชิงลำดับขั้นหรือความสัมพันธ์การรายงานในองค์กร หากต้องการใส่ข้อความในกล่องหัวเรื่อง ให้พิมพ์โดยตรงในรูปสี่เหลี่ยมเล็ก รูปแบบผู้ช่วยและเค้าโครงผังองค์กรแบบห่ายพร้อมให้ใช้กับเค้าโครงนี้ |
| NestedTarget | 74 | ใช้เพื่อแสดงความสัมพันธ์การบรรจุ แต่ละบรรทัดแรกสามบรรทัดของข้อความระดับ 1 ตรงกับข้อความด้านบนซ้ายในรูปและข้อความระดับ 2 ตรงกับรูปขนาดเล็ก ทำงานได้ดีที่สุดกับข้อความระดับ 2 จำนวนเล็กน้อย ข้อความที่ไม่ได้ใช้จะไม่ปรากฏ แต่ยังคงพร้อมใช้งานหากคุณเปลี่ยนเค้าโครง |
| NondirectionalCycle | 75 | ใช้เพื่อแสดงลำดับต่อเนื่องของขั้นตอน งาน หรือเหตุการณ์ในรูปแบบวงกลม แต่ละรูปมีระดับความสำคัญเท่ากัน ทำงานได้ดีเมื่อไม่จำเป็นต้องบ่งบอกทิศทาง |
| OpposingArrows | 76 | ใช้เพื่อแสดงสองแนวคิดที่ตรงกันข้ามหรือแนวคิดที่แตกต่างจากจุดศูนย์กลาง แต่ละบรรทัดแรกสองบรรทัดของข้อความระดับ 1 ตรงกับลูกศร ข้อความที่ไม่ได้ใช้จะไม่ปรากฏ แต่ยังคงพร้อมใช้งานหากคุณเปลี่ยนเค้าโครง |
| OpposingIdeas | 77 | ใช้เพื่อแสดงสองแนวคิดที่ตรงกันข้ามหรือแตกต่าง สามารถมีรายการระดับ 1 หนึ่งหรือสองรายการข้อความระดับ 1 แต่ละรายการสามารถมีหลายระดับย่อย ทำงานได้ดีกับข้อความจำนวนมาก |
| OrganizationChart | 78 | ใช้เพื่อแสดงข้อมูลเชิงลำดับขั้นหรือความสัมพันธ์การรายงานในองค์กร รูปแบบผู้ช่วยและเค้าโครงผังองค์กรแบบห่ายพร้อมให้ใช้กับเค้าโครงนี้ |
| PhasedProcess | 79 | ใช้เพื่อแสดงสามขั้นของกระบวนการ จำกัดที่รายการระดับ 1 จำนวนสามรายการ รายการระดับ 1 สองรายการแรกแต่ละรายการสามารถบรรจุรายการระดับ 2 จำนวนสี่รายการและรายการระดับ 1 ที่สามสามารถบรรจุรายการระดับ 2 ไม่จำกัดจำนวน ทำงานได้ดีที่สุดกับข้อความจำนวนเล็กน้อย |
| PictureAccentBlocks | 80 | ใช้เพื่อแสดงกลุ่มรูปภาพในบล็อกเริ่มจากมุม ข้อความที่สอดคล้องกันแสดงแบบแนวตั้ง ทำงานดีเป็นจุดเน้นบนสไลด์หัวเรื่องหรือหัวเรื่องย่อยหรือเพื่อแบ่งส่วนของเอกสาร |
| PictureAccentList | 81 | ใช้เพื่อแสดงข้อมูลที่จัดกลุ่มหรือเกี่ยวข้อง รูปขนาดเล็กบนมุมบนออกแบบให้บรรจุรูปภาพ เน้นข้อความระดับ 2 มากกว่าระดับ 1 และเป็นตัวเลือกที่ดีสำหรับข้อความระดับ 2 จำนวนมาก |
| PictureAccentProcess | 82 | ใช้เพื่อแสดงขั้นตอนต่อเนื่องในงาน กระบวนการ หรือโฟลว์งาน รูปสี่เหลี่ยมผืนนั้นออกแบบให้บรรจุรูปภาพ |
| PictureCaptionList | 83 | ใช้เพื่อแสดงบล็อกข้อมูลที่ไม่เรียงลำดับหรือจัดกลุ่ม รูปด้านบนออกแบบให้บรรจุรูปภาพและเน้นรูปภาพเหนือข้อความ ทำงานได้ดีสำหรับรูปภาพที่มีคำบรรยายสั้น |
| PictureGrid | 84 | ใช้เพื่อแสดงรูปภาพจัดบนกริดสี่เหลี่ยมจัตุรัส เหมาะกับข้อความระดับ 1 จำนวนเล็กน้อยซึ่งปรากฏเหนือรูปภาพ |
| PictureLineup | 85 | ใช้เพื่อแสดงชุดรูปภาพเรียงข้างกันข้อความระดับ 1 ปกคลุมด้านบนของรูปภาพข้อความระดับ 2 ปรากฏใต้รูปภาพ |
| PictureStrips | 86 | ใช้เพื่อแสดงชุดรูปภาพจากบนลงล่างโดยมีข้อความระดับ 1 อยู่ข้างแต่ละรูป |
| PieProcess | 87 | ใช้เพื่อแสดงขั้นตอนในกระบวนการโดยแต่ละชิ้นพายเพิ่มขนาดสูงสุดถึงเจ็ดรูป ข้อความระดับ 1 แสดงในแนวตั้ง |
| PlusandMinus | 88 | ใช้เพื่อแสดงข้อดีและข้อเสียของสองแนวคิดข้อความระดับ 1 แต่ละรายการสามารถมีหลายระดับย่อย ทำงานได้ดีกับข้อความจำนวนมาก จำกัดที่รายการระดับ 1 จำนวนสองรายการ |
| ProcessArrows | 89 | ใช้เพื่อแสดงข้อมูลที่อธิบายกระบวนการหรือโฟลว์งาน ข้อความระดับ 1 ปรากฏในรูปวงกลมและข้อความระดับ 2 ปรากฏในรูปลูกศร ทำงานได้ดีที่สุดกับข้อความน้อยและเพื่อเน้นการเคลื่อนที่หรือทิศทาง |
| ProcessList | 90 | ใช้เพื่อแสดงหลายกลุ่มของข้อมูลหรือขั้นตอนและขั้นตอนย่อยในงาน กระบวนการ หรือโฟลว์งาน ข้อความระดับ 1 ตรงกับรูปแนวนอนบนสุดและข้อความระดับ 2 ตรงกับขั้นตอนย่อยแนวตั้งใต้รูประดับบนที่เกี่ยวข้องแต่ละรูป |
| PyramidList | 91 | ใช้เพื่อแสดงความสัมพันธ์เชิงสัดส่วน เชื่อมต่อหรือเชิงลำดับขั้น ข้อความปรากฏในรูปสี่เหลี่ยมบนพื้นหลังพีระมิด |
| RadialCluster | 92 | ใช้เพื่อแสดงข้อมูลที่เกี่ยวข้องกับแนวคิดหรือธีมศูนย์กลาง ข้อความระดับ 1 ด้านบนปรากฏตรงกลางข้อความระดับ 2 ปรากฏในรูปรอบ ๆ สามารถมีรูประดับ 2 ได้สูงสุดเจ็ดรูป ข้อความที่ไม่ได้ใช้จะไม่ปรากฏ แต่ยังคงพร้อมใช้งานหากคุณเปลี่ยนเค้าโครง ทำงานได้ดีที่สุดกับข้อความจำนวนเล็กน้อย |
| RadialCycle | 93 | ใช้เพื่อแสดงความสัมพันธ์กับแนวคิดศูนย์กลาง เน้นข้อมูลทั้งในวงกลมกลางและวิธีที่ข้อมูลในวงแหวนรอบนอกมีส่วนช่วยต่อแนวคิดศูนย์กลาง บรรทัดแรกของข้อความระดับ 1 ตรงกับวงกลมกลางและข้อความระดับ 2 ของมันตรงกับวงแหวนรอบนอก ข้อความที่ไม่ได้ใช้จะไม่ปรากฏ แต่ยังคงพร้อมใช้งานหากคุณเปลี่ยนเค้าโครง |
| RadialList | 94 | ใช้เพื่อแสดงความสัมพันธ์กับแนวคิดศูนย์กลางในรอบวง รูปร่างกลางสามารถบรรจุรูปภาพข้อความระดับ 1 ปรากฏในวงกลมขนาดเล็กและข้อความระดับ 2 ที่เกี่ยวข้องใด ๆ ปรากฏด้านข้างของวงกลมขนาดเล็ก |
| RadialVenn | 95 | ใช้เพื่อแสดงทั้งความสัมพันธ์ที่ทับซ้อนและความสัมพันธ์กับแนวคิดศูนย์กลางในรอบวง บรรทัดแรกของข้อความระดับ 1 ตรงกับรูปศูนย์กลางและบรรทัดของข้อความระดับ 2 ตรงกับรูปวงกลมรอบ ๆ ข้อความที่ไม่ได้ใช้จะไม่ปรากฏ แต่ยังคงพร้อมใช้งานหากคุณเปลี่ยนเค้าโครง |
| RandomToResultProcess | 96 | ใช้เพื่อแสดงผ่านลำดับขั้นตอนว่าความคิดวุ่นวายหลายอย่างสามารถนำไปสู่เป้าหมายหรือแนวคิดที่เป็นเอกภาพได้อย่างไร รองรับหลายรายการของข้อความระดับ 1 แต่รูปที่สอดคล้องกับระดับ 1 แรกและสุดท้ายเป็นแบบคงที่ ทำงานได้ดีที่สุดกับข้อความระดับ 1 จำนวนเล็กน้อยและข้อความระดับ 2 ปานกลาง |
| RepeatingBendingProcess | 97 | ใช้เพื่อแสดงการก้าวหน้า หรือขั้นตอนต่อเนื่องในงาน กระบวนการ หรือโฟลว์งาน ให้พื้นที่แสดงรูปในแนวนอนและแนวดิ่งสูงสุด |
| ReverseList | 98 | ใช้เพื่อสลับระหว่างสองรายการ มีแค่สองรายการแรกของข้อความแสดงและแต่ละรายการสามารถบรรจุข้อความจำนวนมาก ทำงานได้ดีเพื่อแสดงการเปลี่ยนแปลงระหว่างสองรายการหรือการเปลี่ยนลำดับ |
| SegmentedCycle | 99 | ใช้เพื่อแสดงการก้าวหน้า หรือลำดับของขั้นตอน งาน หรือเหตุการณ์ในรูปแบบวงกลม เน้นส่วนที่เชื่อมต่อกัน แต่ละบรรทัดแรกเจ็ดบรรทัดของข้อความระดับ 1 ตรงกับรูปสัดส่วนหรือพาย ข้อความที่ไม่ได้ใช้จะไม่ปรากฏ แต่ยังคงพร้อมใช้งานหากคุณเปลี่ยนเค้าโครง |
| SegmentedProcess | 100 | ใช้เพื่อแสดงการก้าวหน้า หรือขั้นตอนต่อเนื่องในงาน กระบวนการ หรือโฟลว์งาน เน้นข้อความระดับ 2 เนื่องจากแต่ละบรรทัดปรากฏในรูปแยกกัน |
| SegmentedPyramid | 101 | ใช้เพื่อแสดงความสัมพันธ์การบรรจุ, เชิงสัดส่วน หรือเชื่อมต่อกัน บรรทัดแรกเก้าบรรทัดของข้อความระดับ 1 ปรากฏในรูปสามเหลี่ยม ข้อความที่ไม่ได้ใช้จะไม่ปรากฏ แต่ยังคงพร้อมใช้งานหากคุณเปลี่ยนเค้าโครง ทำงานได้ดีที่สุดกับข้อความระดับ 1 เท่านั้น |
| SnapshotPictureList | 102 | ใช้เพื่อแสดงรูปภาพพร้อมข้อความอธิบาย ข้อความระดับ 2 สามารถแสดงรายการข้อมูล ทำงานได้ดีกับข้อความจำนวนมาก |
| SpiralPicture | 103 | ใช้เพื่อแสดงชุดรูปภาพสูงสุดห้ารูปพร้อมคำบรรยายระดับ 1 ที่วนเป็นสเปียร์ไปยังศูนย์กลาง |
| SquareAccentList | 104 | ใช้เพื่อแสดงรายการข้อมูลที่แบ่งเป็นประเภท ข้อความระดับ 2 ปรากฏข้างรูปสี่เหลี่ยมเล็ก ทำงานได้ดีกับข้อความระดับ 2 จำนวนมาก |
| StackedList | 105 | ใช้เพื่อแสดงกลุ่มข้อมูลหรือขั้นตอนในงาน กระบวนการ หรือโฟลว์งาน รูปวงกลมบรรจุข้อความระดับ 1 และสี่เหลี่ยมที่สอดคล้องบรรจุข้อความระดับ 2 ทำงานได้ดีสำหรับรายละเอียดจำนวนมากและข้อความระดับ 1 น้อย |
| StackedVenn | 106 | ใช้เพื่อแสดงความสัมพันธ์ที่ทับซ้อน เป็นตัวเลือกที่ดีสำหรับเน้นการเติบโตหรือความค่อยเป็นค่อยไป ทำงานได้ดีที่สุดกับข้อความระดับ 1 เท่านั้น บรรทัดแรกเจ็ดบรรทัดของข้อความระดับ 1 ตรงกับรูปวงกลม ข้อความที่ไม่ได้ใช้จะไม่ปรากฏ แต่ยังคงพร้อมใช้งานหากคุณเปลี่ยนเค้าโครง |
| StaggeredProcess | 107 | ใช้เพื่อแสดงการก้าวลงผ่านขั้นตอนต่าง ๆ แต่ละบรรทัดแรกห้าบรรทัดของข้อความระดับ 1 จะตรงกับสี่เหลี่ยม รูปข้อความที่ไม่ได้ใช้จะไม่แสดง แต่ยังคงพร้อมใช้หากคุณเปลี่ยนเลย์เอาต์ |
| StepDownProcess | 108 | ใช้เพื่อแสดงกระบวนการลงล่างที่มีขั้นตอนหลายขั้นและขั้นย่อย ทำงานได้ดีที่สุดกับข้อความจำนวนเล็ก |
| StepUpProcess | 109 | ใช้เพื่อแสดงชุดขั้นตอนที่เพิ่มขึ้นหรือรายการของข้อมูล |
| SubStepProcess | 110 | ใช้เพื่อแสดงกระบวนการหลายขั้นพร้อมขั้นย่อยระหว่างแต่ละข้อความระดับ 1 ทำงานได้ดีที่สุดกับข้อความจำนวนเล็กและจำกัดที่เจ็ดขั้นระดับ 1 แต่ละขั้นระดับ 1 สามารถมีขั้นย่อยได้ไม่จำกัด |
| TableHierarchy | 111 | ใช้เพื่อแสดงกลุ่มข้อมูลที่สร้างจากบนลงล่างและลำดับขั้นภายในแต่ละกลุ่ม รูปแบบนี้ไม่มีเส้นเชื่อมต่อ |
| TableList | 112 | ใช้เพื่อแสดงข้อมูลที่จัดกลุ่มหรือเกี่ยวข้องที่มีค่าเท่ากัน บรรทัดแรกของข้อความระดับ 1 จะตรงกับรูปร่างบนสุดและข้อความระดับ 2 จะใช้สำหรับรายการต่อไป |
| TargetList | 113 | ใช้เพื่อแสดงข้อมูลที่เชื่อมโยงหรือทับซ้อนกัน แต่ละบรรทัดแรกเจ็ดบรรทัดของข้อความระดับ 1 จะแสดงในรูปสี่เหลี่ยม ข้อความที่ไม่ได้ใช้จะไม่ปรากฏ แต่ยังคงพร้อมใช้หากคุณเปลี่ยนรูปแบบ ทำงานได้ดีทั้งกับข้อความระดับ 1 และระดับ 2 |
| TextCycle | 114 | ใช้เพื่อแสดงลำดับต่อเนื่องของขั้นตอน งาน หรือเหตุการณ์ในรูปแบบวงกลม เน้นลูกศรหรือการไหลมากกว่าขั้นตอนหรือขั้นตอน ทำงานได้ดีที่สุดกับข้อความระดับ 1 เท่านั้น |
| TitlePictureLineup | 115 | ใช้เพื่อแสดงชุดรูปภาพที่แต่ละรูปมีชื่อและรายละเอียดของตนเอง ข้อความระดับ 1 ปรากฏในกล่องเหนือรูปภาพ ข้อความระดับ 2 ปรากฏใต้รูปภาพ |
| TitledMatrix | 116 | ใช้เพื่อแสดงความสัมพันธ์ของสี่สี่เหลี่ยมย่อยต่อทั้งหมด บรรทัดแรกของข้อความระดับ 1 จะตรงกับรูปทรงกลาง และบรรทัดสี่แรกของข้อความระดับ 2 จะปรากฏในสี่เหลี่ยมย่อย ข้อความที่ไม่ได้ใช้จะไม่แสดง แต่ยังคงพร้อมใช้หากคุณเปลี่ยนรูปแบบ |
| TitledPictureAccentList | 117 | ใช้เพื่อแสดงรายการข้อมูลพร้อมรูปภาพเน้นสำหรับข้อความระดับ 2 แต่ละรายการ ข้อความระดับ 1 แสดงในกล่องแยกด้านบนของรายการ |
| TitledPictureBlocks | 118 | ใช้เพื่อแสดงชุดรูปภาพ ข้อความระดับ 1 ปรากฏเหนือแต่ละรูปภาพ ข้อความระดับ 2 ปรากฏด้านข้างและค่อนข้างทับซ้อนกับแต่ละรูปภาพ |
| TrapezoidList | 119 | ใช้เพื่อแสดงข้อมูลที่จัดกลุ่มหรือเกี่ยวข้องที่มีค่าเท่ากัน ทำงานได้ดีกับข้อความจำนวนมาก |
| UpwardArrow | 120 | ใช้เพื่อแสดงการก้าวหน้า หรือขั้นตอนที่แนวโน้มขึ้นในงาน กระบวนการ หรือโฟลว์ การทำงาน แต่ละบรรทัดแรกห้าบรรทัดของข้อความระดับ 1 จะตรงกับจุดบนลูกศร ทำงานได้ดีที่สุดกับข้อความน้อยที่สุด ข้อความที่ไม่ได้ใช้จะไม่แสดง แต่ยังคงพร้อมใช้หากคุณเปลี่ยนรูปแบบ |
| VerticalAccentList | 121 | ใช้เพื่อแสดงรายการข้อมูล ข้อความระดับ 2 ปรากฏในรูปสี่เหลี่ยมเหนือเครื่องหมายลูกศรตั้งแนวตั้ง เน้นข้อความระดับ 2 มากกว่าระดับ 1 และเป็นตัวเลือกที่ดีสำหรับข้อความระดับ 2 ปานกลาง |
| VerticalArrowList | 122 | ใช้เพื่อแสดงการก้าวหน้า หรือขั้นตอนต่อเนื่องในงาน กระบวนการ หรือโฟลว์ที่มุ่งสู่เป้าหมายร่วมกัน ทำงานได้ดีสำหรับรายการแบบหัวข้อสัญลักษณ์ |
| VerticalBendingProcess | 123 | ใช้เพื่อแสดงการก้าวหน้า หรือขั้นตอนต่อเนื่องในงาน กระบวนการ หรือโฟลว์ ใช้พื้นที่การแสดงผลแนวนอนและแนวตั้งของรูปทรงให้เต็มที่สุด เน้นความสัมพันธ์ระหว่างรูปทรงมากกว่าทิศทางหรือการเคลื่อนที่ |
| VerticalBlockList | 124 | ใช้เพื่อแสดงกลุ่มข้อมูลหรือขั้นตอนในงาน กระบวนการ หรือโฟลว์ ทำงานได้ดีกับข้อความระดับ 2 จำนวนมาก เป็นตัวเลือกที่ดีสำหรับข้อความที่มีประเด็นหลักและหลายประเด็นย่อย |
| VerticalBoxList | 125 | ใช้เพื่อแสดงหลายกลุ่มข้อมูลโดยเฉพาะกลุ่มที่มีข้อความระดับ 2 จำนวนมาก เป็นตัวเลือกที่ดีสำหรับรายการข้อมูลแบบหัวข้อสัญลักษณ์ |
| VerticalBulletList | 126 | ใช้เพื่อแสดงบล็อกข้อมูลที่ไม่ต่อเนื่องหรือจัดกลุ่ม ทำงานได้ดีสำหรับรายการที่มีหัวข้อยาวหรือข้อมูลระดับบน |
| VerticalChevronList | 127 | ใช้เพื่อแสดงการก้าวหน้า หรือขั้นตอนต่อเนื่องในงาน กระบวนการ หรือโฟลว์ หรือเพื่อเน้นการเคลื่อนที่หรือทิศทาง เน้นข้อความระดับ 2 มากกว่าระดับ 1 และเป็นตัวเลือกที่ดีสำหรับข้อความระดับ 2 จำนวนมาก |
| VerticalCircleList | 128 | ใช้เพื่อแสดงข้อมูลต่อเนื่องหรือจัดกลุ่ม ทำงานได้ดีที่สุดกับข้อความระดับ 1 ซึ่งแสดงข้างรูประฆังขนาดใหญ่ ระดับข้อความที่ต่ำกว่าแยกด้วยรูประฆังขนาดเล็กกว่า |
| VerticalCurvedList | 129 | ใช้เพื่อแสดงรายการข้อมูลแบบโค้ง เพื่อเพิ่มรูปภาพลงในรูปวงกลมเน้น ให้ใช้การเติมรูปภาพ |
| VerticalEquation | 130 | ใช้เพื่อแสดงขั้นตอนหรือภารกิจต่อเนื่องที่แสดงแผนหรือผลลัพธ์ บรรทัดสุดท้ายของข้อความระดับ 1 ปรากฏหลังลูกศร ทำงานได้ดีที่สุดกับข้อความระดับ 1 เท่านั้น |
| VerticalPictureAccentList | 131 | ใช้เพื่อแสดงบล็อกข้อมูลที่ไม่ต่อเนื่องหรือจัดกลุ่ม วงกลมเล็กออกแบบเพื่อบรรจุรูปภาพ |
| VerticalPictureList | 132 | ใช้เพื่อแสดงบล็อกข้อมูลที่ไม่ต่อเนื่องหรือจัดกลุ่ม รูปทรงเล็กทางด้านซ้ายออกแบบเพื่อบรรจุรูปภาพ |
| VerticalProcess | 133 | ใช้เพื่อแสดงการก้าวหน้า หรือขั้นตอนต่อเนื่องในงาน กระบวนการ หรือโฟลว์จากบนลงล่าง ทำงานได้ดีที่สุดกับข้อความระดับ 1 เนื่องจากพื้นที่แนวตั้งมีจำกัด |
| Custom | 134 | แสดงแผนภาพ [SmartArt](../smartart/) พร้อมเทมเพลตการจัดวางแบบกำหนดเอง |
| PictureOrganizationChart | 135 | ใช้เพื่อแสดงข้อมูลระดับลำดับชั้นหรือความสัมพันธ์การรายงานในองค์กร พร้อมรูปภาพที่สอดคล้อง รูปแบบผู้ช่วยและการจัดวาง Org Chart hanging มีให้ใช้ร่วมกับการจัดวางนี้ |

## ดูเพิ่มเติม

* เนมสเปซ [Aspose::Slides::SmartArt](../)
* ไลบรารี [Aspose.Slides](../../)