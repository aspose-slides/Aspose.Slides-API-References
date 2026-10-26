---
title: Chart
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: เป็นตัวแทนของแผนภูมิกราฟิกบนสไลด์.
type: docs
weight: 53
url: /th/aspose.slides.charts/chart/
---
## คลาส Chart


Represents an graphic chart on a slide.

```cpp
class Chart : public Aspose::Slides::GraphicalObject,
              public Aspose::Slides::Charts::IChart
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) override | เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่าคุณลักษณะของ placeholder ให้เป็นค่าที่ระบุ |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Theme::IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](./createthemeeffective/)() override | ส่งคืนธีมที่ใช้ได้สำหรับชาร์ตนี้ |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนจุดลอยแบบ C# ที่พิจารณา NaN สองค่าให้เท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนจุดลอยแบบ C# ที่พิจารณา NaN สองค่าให้เท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้เพื่อวัตถุประสงค์ภายในเท่านั้น |
| [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/shape/get_alternativetext/)() override | ส่งคืนข้อความแทนที่เชื่อมโยงกับรูปทรง อ่าน [System::String](../../system/string/) |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/shape/get_alternativetexttitle/)() override | ส่งคืนหัวเรื่องของข้อความแทนที่เชื่อมโยงกับรูปทรง อ่าน [System::String](../../system/string/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IAxesManager](../iaxesmanager/)\> [get_Axes](./get_axes/)() override | ให้การเข้าถึงแกนของชาร์ต อ่านอย่างเดียว [IAxesManager](../iaxesmanager/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_BackWall](./get_backwall/)() override | ส่งคืนอ็อบเจ็กต์ที่อนุญาตให้เปลี่ยนรูปแบบของผนังด้านหลังของชาร์ต 3 มิติ อ่านอย่างเดียว [IChartWall](../ichartwall/) |
| [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/shape/get_blackwhitemode/)() override | คุณสมบัติกำหนดว่ารูปทรงจะเรนเดอร์แบบขาว-ดำอย่างไร อ่าน [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartData](../ichartdata/)\> [get_ChartData](./get_chartdata/)() override | ส่งคืนข้อมูลเกี่ยวกับข้อมูลที่เชื่อมโยงหรือฝังไว้กับชาร์ต อ่านอย่างเดียว [IChartData](../ichartdata/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IDataTable](../idatatable/)\> [get_ChartDataTable](./get_chartdatatable/)() override | ส่งคืนตารางข้อมูลของชาร์ต อ่านอย่างเดียว [IDataTable](../idatatable/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_ChartTitle](./get_charttitle/)() override | ส่งคืนหัวเรื่องของชาร์ต อ่านอย่างเดียว [IChartTitle](../icharttitle/) |
| **int32_t** [get_ConnectionSiteCount](../../aspose.slides/shape/get_connectionsitecount/)() override | ส่งคืนจำนวนจุดเชื่อมต่อบนรูปทรง อ่านอย่างเดียว **int32_t** |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/shape/get_customdata/)() override | ส่งคืนข้อมูลกำหนดเองของรูปทรง อ่านอย่างเดียว [ICustomData](../../aspose.slides/icustomdata/) |
| [DisplayBlanksAsType](../displayblanksastype/) [get_DisplayBlanksAs](./get_displayblanksas/)() override | ส่งคืนวิธีการวางเซลล์ว่างบนชาร์ต อ่าน [DisplayBlanksAsType](../displayblanksastype/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/shape/get_effectformat/)() override | ส่งคืนอ็อบเจ็กต์ [EffectFormat](../../aspose.slides/effectformat/) ที่มีเอฟเฟ็กต์พิกเซลที่ใช้กับรูปทรง หมายเหตุ: อาจคืนค่า null สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติเอฟเฟ็กต์ อ่านอย่างเดียว [IEffectFormat](../../aspose.slides/ieffectformat/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/shape/get_fillformat/)() override | ส่งคืนอ็อบเจ็กต์ [FillFormat](../../aspose.slides/fillformat/) ที่มีคุณสมบัติการเติมสีสำหรับรูปทรง หมายเหตุ: อาจคืนค่า null สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติการเติมสี อ่านอย่างเดียว [IFillFormat](../../aspose.slides/ifillformat/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_Floor](./get_floor/)() override | ส่งคืนอ็อบเจ็กต์ที่อนุญาตให้เปลี่ยนรูปแบบของพื้นดินของชาร์ต 3 มิติ อ่านอย่างเดียว [IChartWall](../ichartwall/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/shape/get_frame/)() override | ส่งคืนคุณลักษณะของกรอบรูปทรง อ่าน [IShapeFrame](../../aspose.slides/ishapeframe/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)\> [get_GraphicalObjectLock](../../aspose.slides/graphicalobject/get_graphicalobjectlock/)() override | ส่งคืนการล็อกของรูปทรง อ่านอย่างเดียว [IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/) |
| **bool** [get_HasDataTable](./get_hasdatatable/)() override | ระบุว่าชาร์ตมีตารางข้อมูลหรือไม่ อ่าน **bool** |
| **bool** [get_HasLegend](./get_haslegend/)() override | ระบุว่าชาร์ตมีคำอธิบายหรือไม่ อ่าน **bool** |
| **bool** [get_HasRoundedCorners](./get_hasroundedcorners/)() override | ระบุว่าพื้นที่ชาร์ตต้องมีมุมโค้งอ่าน **bool** |
| **bool** [get_HasTitle](./get_hastitle/)() override | ระบุว่าชาร์ตมีหัวเรื่องที่มองเห็นได้หรือไม่ อ่าน **bool** |
| **float** [get_Height](../../aspose.slides/shape/get_height/)() override | รับความสูงของรูปทรง หน่วยเป็น pt อ่าน **float** |
| **bool** [get_Hidden](../../aspose.slides/shape/get_hidden/)() override | ระบุว่ารูปทรงถูกซ่อนหรือไม่ อ่าน **bool** |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/shape/get_hyperlinkclick/)() override | ส่งคืน hyperlink ที่กำหนดสำหรับคลิกเมาส์ อ่าน [IHyperlink](../../aspose.slides/ihyperlink/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/shape/get_hyperlinkmanager/)() override | ส่งคืนผู้จัดการ hyperlink อ่านอย่างเดียว [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/shape/get_hyperlinkmouseover/)() override | ส่งคืน hyperlink ที่กำหนดสำหรับเมาส์อยู่เหนือ อ่าน [IHyperlink](../../aspose.slides/ihyperlink/) |
| **bool** [get_IsDecorative](../../aspose.slides/shape/get_isdecorative/)() override | รับตัวเลือก 'Mark as decorative' อ่าน/เขียน **bool** |
| **bool** [get_IsGrouped](../../aspose.slides/shape/get_isgrouped/)() override | ระบุว่ารูปทรงถูกจัดกลุ่มหรือไม่ อ่านอย่างเดียว **bool** |
| **bool** [get_IsTextHolder](../../aspose.slides/shape/get_istextholder/)() override | ระบุว่ารูปทรงเป็น TextHolder_PPT หรือไม่ อ่านอย่างเดียว **bool** |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegend](../ilegend/)\> [get_Legend](./get_legend/)() override | ส่งคืนคำอธิบายของชาร์ต อ่านอย่างเดียว [ILegend](../ilegend/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/shape/get_lineformat/)() override | ส่งคืนอ็อบเจ็กต์ [LineFormat](../../aspose.slides/lineformat/) ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปทรง หมายเหตุ: อาจคืนค่า null สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติการจัดรูปแบบเส้น อ่านอย่างเดียว [ILineFormat](../../aspose.slides/ilineformat/) |
| [System::String](../../system/string/) [get_Name](../../aspose.slides/shape/get_name/)() override | ส่งคืนชื่อของรูปทรง ต้องไม่เป็น null ใช้ค่าว่างถ้าจำเป็น อ่าน [System::String](../../system/string/) |
| **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/)() override | ส่งคืนตัวระบุเฉพาะสไลด์ที่คงที่ตลอดอายุของรูปทรงและทำให้ PowerPoint หรือโค้ด interop อ้างอิงรูปทรงได้จากทุกที่ในเอกสาร อ่านอย่างเดียว **uint32_t** ดูเพิ่มเติม [Shape::get_UniqueId](../../aspose.slides/shape/get_uniqueid/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/shape/get_parentgroup/)() override | ส่งคืนอ็อบเจ็กต์ [GroupShape](../../aspose.slides/groupshape/) พาเรนท์หากรูปทรงถูกจัดกลุ่ม มิฉะนั้นคืนค่า null อ่านอย่างเดียว [IGroupShape](../../aspose.slides/igroupshape/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/shape/get_placeholder/)() override | ส่งคืน placeholder ของรูปทรง คืนค่า null หากรูปทรงไม่มี placeholder อ่านอย่างเดียว [IPlaceholder](../../aspose.slides/iplaceholder/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartPlotArea](../ichartplotarea/)\> [get_PlotArea](./get_plotarea/)() override | แทนพื้นที่พล็อตของชาร์ต อ่านอย่างเดียว [IChartPlotArea](../ichartplotarea/) |
| **bool** [get_PlotVisibleCellsOnly](./get_plotvisiblecellsonly/)() override | ระบุว่ามีการวางเฉพาะเซลล์ที่มองเห็นเท่านั้นหรือไม่ False เพื่อวางทั้งเซลล์ที่มองเห็นและซ่อนอ่าน **bool** |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/shape/get_presentation/)() override | ส่งคืนการนำเสนอพาเรนท์ของสไลด์ อ่านอย่างเดียว [IPresentation](../../aspose.slides/ipresentation/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/shape/get_rawframe/)() override | ส่งคืนคุณลักษณะดิบของกรอบรูปทรง อ่าน [IShapeFrame](../../aspose.slides/ishapeframe/) |
| **float** [get_Rotation](../../aspose.slides/shape/get_rotation/)() override | ส่งคืนจำนวนองศาที่รูปทรงหมุนรอบแกน z ค่าเป็นบวกหมายถึงการหมุนตามเข็มนาฬิกา ค่าเป็นลบหมายถึงการหมุนทวนเข็มนาฬิกา อ่าน **float** |
| [System::SharedPtr](../../system/sharedptr/)\<[IRotation3D](../irotation3d/)\> [get_Rotation3D](./get_rotation3d/)() override | ส่งคืนการหมุน 3D ของชาร์ต อ่านอย่างเดียว [IRotation3D](../irotation3d/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/shape/get_shapelock/)() override | ส่งคืนการล็อกของรูปทรง อ่านอย่างเดียว [IBaseShapeLock](../../aspose.slides/ibaseshapelock/) |
| **bool** [get_ShowDataLabelsOverMaximum](./get_showdatalabelsovermaximum/)() override | ระบุว่าต้องแสดงป้ายกำกับข้อมูลเหนือค่ามากสุดของชาร์ตหรือไม่ อ่าน **bool** |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_SideWall](./get_sidewall/)() override | ส่งคืนอ็อบเจ็กต์ที่อนุญาตให้เปลี่ยนรูปแบบของผนังด้านข้างของชาร์ต 3 มิติ อ่านอย่างเดียว [IChartWall](../ichartwall/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/shape/get_slide/)() override | ส่งคืนสไลด์พาเรนท์ของรูปทรง อ่านอย่างเดียว [IBaseSlide](../../aspose.slides/ibaseslide/) |
| [StyleType](../styletype/) [get_Style](./get_style/)() override | ส่งคืนสไตล์ของชาร์ต อ่าน [StyleType](../styletype/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | ส่งคืนรูปแบบข้อความของชาร์ต คุณลักษณะนี้ไม่สามารถใช้ได้กับประเภทต่อไปนี้: [ChartType::Treemap](../charttype/), [ChartType::Sunburst](../charttype/), [ChartType::Waterfall](../charttype/), [ChartType::Histogram](../charttype/), [ChartType::Funnel](../charttype/),[ChartType::BoxAndWhisker](../charttype/) อ่านอย่างเดียว [IChartTextFormat](../icharttextformat/) |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Theme::IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/)\> [get_ThemeManager](./get_thememanager/)() override | ส่งคืนผู้จัดการธีม อ่านอย่างเดียว [Aspose::Slides::Theme::IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/shape/get_threedformat/)() override | ส่งคืนอ็อบเจ็กต์ [ThreeDFormat](../../aspose.slides/threedformat/) ที่มีคุณสมบัติโพรเซส 3d สำหรับรูปทรง หมายเหตุ: อาจคืนค่า null สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติ 3d อ่านอย่างเดียว [IThreeDFormat](../../aspose.slides/ithreedformat/) |
| [ChartType](../charttype/) [get_Type](./get_type/)() override | ส่งคืนประเภทของชาร์ต อ่าน [ChartType](../charttype/) |
| **uint32_t** [get_UniqueId](../../aspose.slides/shape/get_uniqueid/)() override | ส่งคืนตัวระบุภายในที่ใช้ระดับการนำเสนอสำหรับส่วนเสริมหรือโค้ดอื่น ๆ เนื่องจากค่าดังกล่าวอาจถูกเปลี่ยนโดยผู้ใช้หรือโปรแกรม ไม่ควรถือว่าเป็นคีย์ที่คงที่ อ่านอย่างเดียว **uint32_t** ดูเพิ่มเติม [Shape::get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_UserShapes](./get_usershapes/)() override | ระบุรูปทรงที่วาดเหนือชาร์ต อ่านอย่างเดียว [IGroupShape](../../aspose.slides/igroupshape/) |
| **float** [get_Width](../../aspose.slides/shape/get_width/)() override | รับความกว้างของรูปทรง หน่วยเป็น pt อ่าน **float** |
| **float** [get_X](../../aspose.slides/shape/get_x/)() override | รับค่า x-coordinate ของมุมซ้ายบนของรูปทรง หน่วยเป็น pt อ่าน **float** |
| **float** [get_Y](../../aspose.slides/shape/get_y/)() override | รับค่า y-coordinate ของมุมซ้ายบนของรูปทรง หน่วยเป็น pt อ่าน **float** |
| **int32_t** [get_ZOrderPosition](../../aspose.slides/shape/get_zorderposition/)() override | ส่งคืนตำแหน่งของรูปทรงในลำดับ z Shapes[0] คืนรูปทรงที่อยู่ด้านหลังสุด และ Shapes[Shapes.Count - 1] คืนรูปทรงที่อยู่ด้านหน้าสุด อ่านอย่างเดียว **int32_t** |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder/)() override | ส่งคืนรูป placeholder พื้นฐาน (รูปจากเลย์เอาต์หรือมาสเตอร์สไลด์ที่รูปปัจจุบันสืบทอดมาลง) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | ความคล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) เปิดใช้งานการแฮชของอ็อบเจ็กต์กำหนดเอง |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)() override | ส่งคืนภาพย่อของรูปทรง [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/) ชนิดขอบเขตภาพย่อของรูปทรงถูกใช้เป็นค่าเริ่มต้น |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) override | ส่งคืนภาพย่อของรูปทรง |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์ ความคล้ายกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../../aspose.slides/shape/getvisualbounds/)() | รับขอบเขตภาพของรูปทรงที่คำนวณจากเนื้อหาที่แสดงผล |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ ความคล้ายกับโอเปอเรเตอร์ C# 'is' |
| void [Lock](../../system/object/lock/)() | ทำตามคำสั่ง lock() ของ C# เพื่อล็อก เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | ความคล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) เปิดใช้งานการโคลนประเภทกำหนดเอง |
| [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา ไม่คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการสำเนาสำหรับคลาสย่อย |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า ไม่คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการสำเนาสำหรับคลาสย่อย |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์ตามการอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์ตามการอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะสำหรับ [Object::ReferenceEquals](../../system/object/referenceequals/) ในกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะสำหรับ [Object::ReferenceEquals](../../system/object/referenceequals/) ในกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดตัวนับอ้างอิงที่แชร์ตามค่าที่ระบุ |
| void [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder/)() override | ระบุว่ารูปทรงนี้ไม่ใช่ placeholder |
| void [set_AlternativeText](../../aspose.slides/shape/set_alternativetext/)([System::String](../../system/string/)) override | ตั้งค่าข้อความแทนที่เชื่อมโยงกับรูปทรง เขียน [System::String](../../system/string/) |
| void [set_AlternativeTextTitle](../../aspose.slides/shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | ตั้งค่าหัวเรื่องของข้อความแทนที่เชื่อมโยงกับรูปทรง เขียน [System::String](../../system/string/) |
| void [set_BlackWhiteMode](../../aspose.slides/shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) override | คุณสมบัติกำหนดว่ารูปทรงจะเรนเดอร์แบบขาว-ดำอย่างไร เขียน [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) |
| void [set_DisplayBlanksAs](./set_displayblanksas/)([DisplayBlanksAsType](../displayblanksastype/)) override | ตั้งค่าวิธีการวางเซลล์ว่างบนชาร์ต เขียน [DisplayBlanksAsType](../displayblanksastype/) |
| void [set_Frame](../../aspose.slides/shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | ตั้งค่าคุณลักษณะของกรอบรูปทรง เขียน [IShapeFrame](../../aspose.slides/ishapeframe/) |
| void [set_HasDataTable](./set_hasdatatable/)(**bool**) override | ระบุว่าชาร์ตมีตารางข้อมูลหรือไม่ เขียน **bool** |
| void [set_HasLegend](./set_haslegend/)(**bool**) override | ระบุว่าชาร์ตมีคำอธิบายหรือไม่ เขียน **bool** |
| void [set_HasRoundedCorners](./set_hasroundedcorners/)(**bool**) override | ระบุว่าพื้นที่ชาร์ตต้องมีมุมโค้ง เขียน **bool** |
| void [set_HasTitle](./set_hastitle/)(**bool**) override | ระบุว่าชาร์ตมีหัวเรื่องที่มองเห็นได้หรือไม่ เขียน **bool** |
| void [set_Height](../../aspose.slides/shape/set_height/)(**float**) override | ตั้งค่าความสูงของรูปทรง หน่วยเป็น pt เขียน **float** |
| void [set_Hidden](../../aspose.slides/shape/set_hidden/)(**bool**) override | ระบุว่ารูปทรงถูกซ่อนหรือไม่ เขียน **bool** |
| void [set_HyperlinkClick](../../aspose.slides/shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | ตั้งค่าลิงก์ที่กำหนดสำหรับคลิกเมาส์ เขียน [IHyperlink](../../aspose.slides/ihyperlink/) |
| void [set_HyperlinkMouseOver](../../aspose.slides/shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | ตั้งค่าลิงก์ที่กำหนดสำหรับเมาส์อยู่เหนือ เขียน [IHyperlink](../../aspose.slides/ihyperlink/) |
| void [set_IsDecorative](../../aspose.slides/shape/set_isdecorative/)(**bool**) override | ตั้งค่าตัวเลือก 'Mark as decorative' อ่าน/เขียน **bool** |
| void [set_Name](../../aspose.slides/shape/set_name/)([System::String](../../system/string/)) override | ตั้งค่าชื่อของรูปทรง ต้องไม่เป็น null ใช้ค่าว่างถ้าจำเป็น เขียน [System::String](../../system/string/) |
| void [set_PlotVisibleCellsOnly](./set_plotvisiblecellsonly/)(**bool**) override | ระบุว่ามีการวางเฉพาะเซลล์ที่มองเห็นหรือไม่ False เพื่อวางทั้งเซลล์ที่มองเห็นและซ่อน เขียน **bool** |
| void [set_RawFrame](../../aspose.slides/shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | ตั้งค่าคุณลักษณะดิบของกรอบรูปทรง เขียน [IShapeFrame](../../aspose.slides/ishapeframe/) |
| void [set_Rotation](../../aspose.slides/shape/set_rotation/)(**float**) override | ตั้งค่าจำนวนองศาที่รูปทรงหมุนรอบแกน z ค่าเป็นบวกหมายถึงการหมุนตามเข็มนาฬิกา ค่าเป็นลบหมายถึงการหมุนทวนเข็มนาฬิกา เขียน **float** |
| void [set_ShowDataLabelsOverMaximum](./set_showdatalabelsovermaximum/)(**bool**) override | ระบุว่าต้องแสดงป้ายกำกับข้อมูลเหนือค่ามากสุดของชาร์ตหรือไม่ เขียน **bool** |
| void [set_Style](./set_style/)([StyleType](../styletype/)) override | ตั้งค่าสไตล์ของชาร์ต เขียน [StyleType](../styletype/) |
| void [set_Type](./set_type/)([ChartType](../charttype/)) override | ตั้งค่าประเภทของชาร์ต เขียน [ChartType](../charttype/) |
| void [set_Width](../../aspose.slides/shape/set_width/)(**float**) override | ตั้งค่าความกว้างของรูปทรง หน่วยเป็น pt เขียน **float** |
| void [set_X](../../aspose.slides/shape/set_x/)(**float**) override | ตั้งค่าค่า x-coordinate ของมุมซ้ายบนของรูปทรง หน่วยเป็น pt เขียน **float** |
| void [set_Y](../../aspose.slides/shape/set_y/)(**float**) override | ตั้งค่าค่า y-coordinate ของมุมซ้ายบนของรูปทรง หน่วยเป็น pt เขียน **float** |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n เป็น weak pointer (แทน shared) ให้สามารถสลับ pointer ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง ใช้ smart pointer หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง ใช้ smart pointer หรือ ThisProtector แทน |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | ความคล้ายกับเมธอด C# [Object.ToString()](../../system/object/tostring/) เปิดใช้งานการแปลงอ็อบเจ็กต์กำหนดเองเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำตามคำสั่ง typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ทำตามคำสั่ง unlock() ของ C# เพื่อปลดล็อก เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| void [ValidateChartLayout](./validatechartlayout/)() override | คำนวณค่าจริงขององค์ประกอบชาร์ต ค่าจริงรวมถึงตำแหน่งขององค์ประกอบที่ทำตามอินเทอร์เฟซ [IActualLayout](../iactuallayout/) ([IActualLayout::get_ActualX](../iactuallayout/get_actualx/), [IActualLayout::get_ActualY](../iactuallayout/get_actualy/), [IActualLayout::get_ActualWidth](../iactuallayout/get_actualwidth/), [IActualLayout::get_ActualHeight](../iactuallayout/get_actualheight/)) และค่าจริงของแกน ([IAxis::get_ActualMaxValue](../iaxis/get_actualmaxvalue/), [IAxis::get_ActualMinValue](../iaxis/get_actualminvalue/), [IAxis::get_ActualMajorUnit](../iaxis/get_actualmajorunit/), [IAxis::get_ActualMinorUnit](../iaxis/get_actualminorunit/), [IAxis::get_ActualMajorUnitScale](../iaxis/get_actualmajorunitscale/), [IAxis::get_ActualMinorUnitScale](../iaxis/get_actualminorunitscale/)) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง ใช้ smart pointer หรือ ThisProtector แทน |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง ใช้ smart pointer หรือ ThisProtector แทน |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | บันทึกเนื้อหาของ [Shape](../../aspose.slides/shape/) เป็นไฟล์ SVG |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | บันทึกเนื้อหาของ [Shape](../../aspose.slides/shape/) เป็นไฟล์ SVG |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [GraphicalObject](../../aspose.slides/graphicalobject/)
* คลาส [IChart](../ichart/)
* เนมสเปซ [Aspose::Slides::Charts](../)
* ไลบรารี [Aspose.Slides](../../)