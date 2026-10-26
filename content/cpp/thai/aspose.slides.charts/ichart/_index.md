---
title: IChart
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แทนแผนภูมิกราฟิกบนสไลด์.
type: docs
weight: 573
url: /th/aspose.slides.charts/ichart/
---
## IChart คลาส


Represents an graphic chart on a slide.

```cpp
class IChart : public virtual Aspose::Slides::IGraphicalObject,
               public Aspose::Slides::Charts::IFormattedTextContainer,
               public Aspose::Slides::Theme::IOverrideThemeable
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) | เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่าคุณสมบัติของ placeholder ให้เป็นค่าที่ระบุ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](../../aspose.slides.theme/ithemeable/createthemeeffective/)() | คืนค่าธีมที่ใช้งานได้สำหรับวัตถุที่สามารถตั้งธีมได้นี้ |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้หลักการของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทค่าในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่า float แบบ C# โดยที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่า double แบบ C# โดยที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น |
| virtual [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/ishape/get_alternativetext/)() | คืนข้อความแทนที่เชื่อมโยงกับรูปทรง อ่าน [System::String](../../system/string/) |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/ishape/get_alternativetexttitle/)() | คืนชื่อเรื่องของข้อความแทนที่เชื่อมโยงกับรูปทรง อ่าน [System::String](../../system/string/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAxesManager](../iaxesmanager/)\> [get_Axes](./get_axes/)() | ให้การเข้าถึงแกนของแผนภูมิ อ่านอย่างเดียว [IAxesManager](../iaxesmanager/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_BackWall](./get_backwall/)() | คืนอ็อบเจ็กต์ที่ให้เปลี่ยนรูปแบบของผนังด้านหลังของแผนภูมิ 3 มิติ อ่านอย่างเดียว [IChartWall](../ichartwall/) |
| virtual [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/ishape/get_blackwhitemode/)() | คุณสมบัติกำหนดว่ารูปทรงจะเรนเดอร์อย่างไรในโหมดแสดงผลสีขาว-ดำ อ่าน [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](./)\> [get_Chart](../ichartcomponent/get_chart/)() | คืนแผนภูมิ อ่านอย่างเดียว [IChart](./) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartData](../ichartdata/)\> [get_ChartData](./get_chartdata/)() | คืนข้อมูลเกี่ยวกับข้อมูลที่เชื่อมโยงหรือฝังที่เชื่อมโยงกับแผนภูมิ อ่านอย่างเดียว [IChartData](../ichartdata/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDataTable](../idatatable/)\> [get_ChartDataTable](./get_chartdatatable/)() | คืนตารางข้อมูลของแผนภูมิ อ่านอย่างเดียว [IDataTable](../idatatable/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_ChartTitle](./get_charttitle/)() | คืนชื่อหัวข้อของแผนภูมิ อ่านอย่างเดียว [IChartTitle](../icharttitle/) |
| virtual **int32_t** [get_ConnectionSiteCount](../../aspose.slides/ishape/get_connectionsitecount/)() | คืนจำนวนจุดเชื่อมต่อบนรูปทรง อ่านอย่างเดียว **int32_t** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/ishape/get_customdata/)() | คืนข้อมูลแบบกำหนดเองของรูปทรง อ่านอย่างเดียว [ICustomData](../../aspose.slides/icustomdata/) |
| virtual [DisplayBlanksAsType](../displayblanksastype/) [get_DisplayBlanksAs](./get_displayblanksas/)() | คืนวิธีการวาดเซลล์ว่างบนแผนภูมิ อ่าน [DisplayBlanksAsType](../displayblanksastype/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/ishape/get_effectformat/)() | คืนอ็อบเจ็กต์ [EffectFormat](../../aspose.slides/effectformat/) ที่มีเอฟเฟกต์พิกเซลที่ใช้กับรูปทรง อ่านอย่างเดียว [IEffectFormat](../../aspose.slides/ieffectformat/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/ishape/get_fillformat/)() | คืนอ็อบเจ็กต์ [FillFormat](../../aspose.slides/fillformat/) ที่มีคุณสมบัติการจัดรูปแบบการเติมสำหรับรูปทรง อ่านอย่างเดียว [IFillFormat](../../aspose.slides/ifillformat/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_Floor](./get_floor/)() | คืนอ็อบเจ็กต์ที่ให้เปลี่ยนรูปแบบของพื้นของแผนภูมิ 3 มิติ อ่านอย่างเดียว [IChartWall](../ichartwall/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/ishape/get_frame/)() | คืนคุณสมบัติของเฟรมรูปทรง อ่าน [IShapeFrame](../../aspose.slides/ishapeframe/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)\> [get_GraphicalObjectLock](../../aspose.slides/igraphicalobject/get_graphicalobjectlock/)() | คืนการล็อกของรูปทรง อ่านอย่างเดียว [IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/) |
| virtual **bool** [get_HasDataTable](./get_hasdatatable/)() | กำหนดว่าแผนภูมิมีตารางข้อมูลหรือไม่ อ่าน **bool** |
| virtual **bool** [get_HasLegend](./get_haslegend/)() | กำหนดว่าแผนภูมิมีคำอธิบายหรือไม่ อ่าน **bool** |
| virtual **bool** [get_HasRoundedCorners](./get_hasroundedcorners/)() | ระบุว่าเขตพื้นที่แผนภูมิควรมีมุมโค้ง อ่าน **bool** |
| virtual **bool** [get_HasTitle](./get_hastitle/)() | กำหนดว่าแผนภูมิมีชื่อที่มองเห็นได้หรือไม่ อ่าน **bool** |
| virtual **float** [get_Height](../../aspose.slides/ishape/get_height/)() | รับความสูงของรูปทรง หน่วยเป็นพอยต์ อ่าน **float** |
| virtual **bool** [get_Hidden](../../aspose.slides/ishape/get_hidden/)() | กำหนดว่ารูปทรงถูกซ่อนหรือไม่ อ่าน **bool** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkclick/)() | คืน hyperlink ที่กำหนดสำหรับคลิกเมาส์ อ่าน [IHyperlink](../../aspose.slides/ihyperlink/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmanager/)() | ผู้จัดการ hyperlink อ่านอย่างเดียว [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmouseover/)() | คืน hyperlink ที่กำหนดสำหรับเมาส์โอเวอร์ อ่าน [IHyperlink](../../aspose.slides/ihyperlink/) |
| virtual **bool** [get_IsDecorative](../../aspose.slides/ishape/get_isdecorative/)() | รับตัวเลือก 'Mark as decorative' อ่าน/เขียน **bool** |
| virtual **bool** [get_IsGrouped](../../aspose.slides/ishape/get_isgrouped/)() | กำหนดว่ารูปทรงถูกจัดกลุ่มหรือไม่ อ่านอย่างเดียว **bool** |
| virtual **bool** [get_IsTextHolder](../../aspose.slides/ishape/get_istextholder/)() | กำหนดว่ารูปทรงเป็น TextHolder หรือไม่ อ่านอย่างเดียว **bool** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegend](../ilegend/)\> [get_Legend](./get_legend/)() | คืนคำอธิบายสำหรับแผนภูมิ อ่านอย่างเดียว [ILegend](../ilegend/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/ishape/get_lineformat/)() | คืนอ็อบเจ็กต์ [LineFormat](../../aspose.slides/lineformat/) ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปทรง อ่านอย่างเดียว [ILineFormat](../../aspose.slides/ilineformat/) |
| virtual [System::String](../../system/string/) [get_Name](../../aspose.slides/ishape/get_name/)() | คืนชื่อของรูปทรง อ่าน [System::String](../../system/string/) |
| virtual **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/)() | คืนตัวระบุเฉพาะที่จำกัดอยู่ในสไลด์ ซึ่งคงที่ตลอดอายุของรูปทรงและทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปทรงจากทุกที่ในเอกสารได้อย่างเชื่อถือได้ อ่านอย่างเดียว **uint32_t**. ดูเพิ่มเติม [IShape::get_UniqueId](../../aspose.slides/ishape/get_uniqueid/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/ishape/get_parentgroup/)() | คืนอ็อบเจ็กต์ [GroupShape](../../aspose.slides/groupshape/) ระดับพาเรนท์หากรูปทรงถูกจัดกลุ่ม มิฉะนั้นคืนค่า null อ่านอย่างเดียว [IGroupShape](../../aspose.slides/igroupshape/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/ishape/get_placeholder/)() | คืน placeholder สำหรับรูปทรง อ่านอย่างเดียว [IPlaceholder](../../aspose.slides/iplaceholder/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartPlotArea](../ichartplotarea/)\> [get_PlotArea](./get_plotarea/)() | เป็นตัวแทนของพื้นที่กราฟของแผนภูมิ อ่านอย่างเดียว [IChartPlotArea](../ichartplotarea/) |
| virtual **bool** [get_PlotVisibleCellsOnly](./get_plotvisiblecellsonly/)() | กำหนดว่าจะแสดงเฉพาะเซลล์ที่มองเห็นได้หรือไม่ ค่า false เพื่อแสดงทั้งเซลล์ที่มองเห็นและซ่อน อ่าน **bool** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | คืนการนำเสนอ อ่านอย่างเดียว [IPresentation](../../aspose.slides/ipresentation/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/ishape/get_rawframe/)() | คืนคุณสมบัติของเฟรมรูปทรงดิบ อ่าน [IShapeFrame](../../aspose.slides/ishapeframe/) |
| virtual **float** [get_Rotation](../../aspose.slides/ishape/get_rotation/)() | คืนจำนวนองศาที่รูปทรงที่ระบุหมุนรอบแกน z ค่าเป็นบวกบ่งบอกการหมุนตามเข็มนาฬิกา ค่าเป็นลบบ่งบอกการหมุนทวนเข็มนาฬิกา อ่าน **float** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IRotation3D](../irotation3d/)\> [get_Rotation3D](./get_rotation3d/)() | คืนการหมุน 3 มิติของแผนภูมิ อ่านอย่างเดียว [IRotation3D](../irotation3d/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/ishape/get_shapelock/)() | คืนการล็อกของรูปทรง อ่านอย่างเดียว [IBaseShapeLock](../../aspose.slides/ibaseshapelock/) |
| virtual **bool** [get_ShowDataLabelsOverMaximum](./get_showdatalabelsovermaximum/)() | ระบุว่าตำแหน่งข้อมูลเหนือค่าสูงสุดของแผนภูมิจะถูกแสดง อ่าน **bool** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_SideWall](./get_sidewall/)() | คืนอ็อบเจ็กต์ที่ให้เปลี่ยนรูปแบบของผนังด้านข้างของแผนภูมิ 3 มิติ อ่านอย่างเดียว [IChartWall](../ichartwall/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | คืนสไลด์ฐาน อ่านอย่างเดียว [IBaseSlide](../../aspose.slides/ibaseslide/) |
| virtual [StyleType](../styletype/) [get_Style](./get_style/)() | คืนสไตล์แผนภูมิ อ่าน [StyleType](../styletype/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | คืนรูปแบบข้อความของแผนภูมิ อ่านอย่างเดียว [IChartTextFormat](../icharttextformat/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/)\> [get_ThemeManager](../../aspose.slides.theme/ioverridethemeable/get_thememanager/)() | คืนผู้จัดการธีมทับซ้อน อ่านอย่างเดียว [IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/ishape/get_threedformat/)() | คืนอ็อบเจ็กต์ [ThreeDFormat](../../aspose.slides/threedformat/) ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปทรง อ่านอย่างเดียว [IThreeDFormat](../../aspose.slides/ithreedformat/) |
| virtual [ChartType](../charttype/) [get_Type](./get_type/)() | คืนประเภทแผนภูมิ อ่าน [ChartType](../charttype/) |
| virtual **uint32_t** [get_UniqueId](../../aspose.slides/ishape/get_uniqueid/)() | คืนตัวระบุภายในที่จำกัดอยู่ในการนำเสนอ ซึ่งตั้งใจใช้โดยแอดอินหรือโค้ดอื่น ๆ เนื่องจากค่าดังกล่าวสามารถถูกกำหนดใหม่โดยผู้ใช้หรือโปรแกรมได้ จึงไม่ควรถือเป็นคีย์ที่คงที่เฉพาะ อ่านอย่างเดียว **uint32_t**. ดูเพิ่มเติม [IShape::get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_UserShapes](./get_usershapes/)() | ระบุรูปทรงที่วาดอยู่ด้านบนของแผนภูมิ อ่านอย่างเดียว [IGroupShape](../../aspose.slides/igroupshape/) |
| virtual **float** [get_Width](../../aspose.slides/ishape/get_width/)() | รับความกว้างของรูปทรง หน่วยเป็นพอยต์ อ่าน **float** |
| virtual **float** [get_X](../../aspose.slides/ishape/get_x/)() | รับค่าพิกัด x ของมุมซ้ายบนของรูปทรง หน่วยเป็นพอยต์ อ่าน **float** |
| virtual **float** [get_Y](../../aspose.slides/ishape/get_y/)() | รับค่าพิกัด y ของมุมซ้ายบนของรูปทรง หน่วยเป็นพอยต์ อ่าน **float** |
| virtual **int32_t** [get_ZOrderPosition](../../aspose.slides/ishape/get_zorderposition/)() | คืนตำแหน่งของรูปทรงในลำดับ z Shapes[0] คืนรูปทรงที่อยู่ด้านหลังของลำดับ z และ Shapes[Shapes.Count - 1] คืนรูปทรงที่อยู่ด้านหน้าของลำดับ z อ่านอย่างเดียว **int32_t** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder/)() | คืนรูป placeholder เบื้องต้น (รูปจากเค้าโครงและ/หรือสไลด์หลักที่รูปปัจจุบันสืบทอดมาจาก) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นแบบจำลองของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการทำแฮชของอ็อบเจ็กต์แบบกำหนดเอง |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)() | คืนภาพย่อของรูปทรง [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/) ประเภทขอบเขตภาพย่อของรูปทรงจะถูกใช้เป็นค่าเริ่มต้น |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) | คืนภาพย่อของรูปทรง |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. เป็นแบบจำลองของการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นแบบจำลองของออปเพอเรเตอร์ C# 'is' |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่ล็อกตามคำสั่ง C# lock() . เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นแบบจำลองของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทแบบกำหนดเอง |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา. ไม่ได้ทำการคัดลอกใด ๆ จริง ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการสำเนาคลาสย่อย |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า. ไม่ได้ทำการคัดลอกใด ๆ จริง ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการสำเนาคลาสย่อย |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | อ้างอิงเปรียบเทียบอ็อบเจ็กต์ประเภทค่ากับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเจาะจงของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเจาะจงของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงที่แชร์โดยค่าที่ระบุ |
| virtual void [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder/)() | กำหนดว่ารูปทรงนี้ไม่ใช่ placeholder |
| virtual void [set_AlternativeText](../../aspose.slides/ishape/set_alternativetext/)([System::String](../../system/string/)) | ตั้งข้อความแทนที่เชื่อมโยงกับรูปทรง เขียน [System::String](../../system/string/) |
| virtual void [set_AlternativeTextTitle](../../aspose.slides/ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | ตั้งชื่อเรื่องของข้อความแทนที่เชื่อมโยงกับรูปทรง เขียน [System::String](../../system/string/) |
| virtual void [set_BlackWhiteMode](../../aspose.slides/ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) | คุณสมบัติกำหนดว่ารูปทรงจะเรนเดอร์อย่างไรในโหมดแสดงผลสีขาว-ดำ เขียน [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) |
| virtual void [set_DisplayBlanksAs](./set_displayblanksas/)([DisplayBlanksAsType](../displayblanksastype/)) | ตั้งวิธีการวาดเซลล์ว่างบนแผนภูมิ เขียน [DisplayBlanksAsType](../displayblanksastype/) |
| virtual void [set_Frame](../../aspose.slides/ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | ตั้งค่าคุณสมบัติของเฟรมรูปทรง เขียน [IShapeFrame](../../aspose.slides/ishapeframe/) |
| virtual void [set_HasDataTable](./set_hasdatatable/)(**bool**) | กำหนดว่าแผนภูมิมีตารางข้อมูลหรือไม่ เขียน **bool** |
| virtual void [set_HasLegend](./set_haslegend/)(**bool**) | กำหนดว่าแผนภูมิมีคำอธิบายหรือไม่ เขียน **bool** |
| virtual void [set_HasRoundedCorners](./set_hasroundedcorners/)(**bool**) | ระบุว่าเขตพื้นที่แผนภูมิควรมีมุมโค้ง เขียน **bool** |
| virtual void [set_HasTitle](./set_hastitle/)(**bool**) | กำหนดว่าแผนภูมิมีชื่อที่มองเห็นได้หรือไม่ เขียน **bool** |
| virtual void [set_Height](../../aspose.slides/ishape/set_height/)(**float**) | ตั้งความสูงของรูปทรง หน่วยเป็นพอยต์ เขียน **float** |
| virtual void [set_Hidden](../../aspose.slides/ishape/set_hidden/)(**bool**) | กำหนดว่ารูปทรงถูกซ่อนหรือไม่ เขียน **bool** |
| virtual void [set_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | ตั้ง hyperlink ที่กำหนดสำหรับคลิกเมาส์ เขียน [IHyperlink](../../aspose.slides/ihyperlink/) |
| virtual void [set_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | ตั้ง hyperlink ที่กำหนดสำหรับเมาส์โอเวอร์ เขียน [IHyperlink](../../aspose.slides/ihyperlink/) |
| virtual void [set_IsDecorative](../../aspose.slides/ishape/set_isdecorative/)(**bool**) | ตั้งตัวเลือก 'Mark as decorative' อ่าน/เขียน **bool** |
| virtual void [set_Name](../../aspose.slides/ishape/set_name/)([System::String](../../system/string/)) | ตั้งชื่อของรูปทรง เขียน [System::String](../../system/string/) |
| virtual void [set_PlotVisibleCellsOnly](./set_plotvisiblecellsonly/)(**bool**) | กำหนดว่าจะแสดงเฉพาะเซลล์ที่มองเห็นได้หรือไม่ ค่า false เพื่อแสดงทั้งเซลล์ที่มองเห็นและซ่อน เขียน **bool** |
| virtual void [set_RawFrame](../../aspose.slides/ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | ตั้งค่าคุณสมบัติของเฟรมรูปทรงดิบ เขียน [IShapeFrame](../../aspose.slides/ishapeframe/) |
| virtual void [set_Rotation](../../aspose.slides/ishape/set_rotation/)(**float**) | ตั้งจำนวนองศาที่รูปทรงที่ระบุหมุนรอบแกน z ค่าเป็นบวกบ่งบอกการหมุนตามเข็มนาฬิกา ค่าเป็นลบบ่งบอกการหมุนทวนเข็มนาฬิกา เขียน **float** |
| virtual void [set_ShowDataLabelsOverMaximum](./set_showdatalabelsovermaximum/)(**bool**) | ระบุว่าตำแหน่งข้อมูลเหนือค่าสูงสุดของแผนภูมิจะถูกแสดง เขียน **bool** |
| virtual void [set_Style](./set_style/)([StyleType](../styletype/)) | ตั้งสไตล์แผนภูมิ เขียน [StyleType](../styletype/) |
| virtual void [set_Type](./set_type/)([ChartType](../charttype/)) | ตั้งประเภทแผนภูมิ เขียน [ChartType](../charttype/) |
| virtual void [set_Width](../../aspose.slides/ishape/set_width/)(**float**) | ตั้งความกว้างของรูปทรง หน่วยเป็นพอยต์ เขียน **float** |
| virtual void [set_X](../../aspose.slides/ishape/set_x/)(**float**) | ตั้งค่าพิกัด x ของมุมซ้ายบนของรูปทรง หน่วยเป็นพอยต์ เขียน **float** |
| virtual void [set_Y](../../aspose.slides/ishape/set_y/)(**float**) | ตั้งค่าพิกัด y ของมุมซ้ายบนของรูปทรง หน่วยเป็นพอยต์ เขียน **float** |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งอาร์กูเมนต์เทมเพลตที่ n เป็น weak pointer (แทนที่ shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; แทนที่ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนและคืนค่าตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; แทนที่ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นแบบจำลองของเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์แบบกำหนดเองเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่สร้างโครงสร้าง C# typeof([System.Object](../../system/object/)) |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง C# lock() . เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual void [ValidateChartLayout](./validatechartlayout/)() | คำนวณค่าจริงขององค์ประกอบแผนภูมิ. ค่าจริงรวมถึงตำแหน่งขององค์ประกอบที่ทำตามอินเทอร์เฟซ [IActualLayout](../iactuallayout/) ([IActualLayout::get_ActualX](../iactuallayout/get_actualx/), [IActualLayout::get_ActualY](../iactuallayout/get_actualy/), [IActualLayout::get_ActualWidth](../iactuallayout/get_actualwidth/), [IActualLayout::get_ActualHeight](../iactuallayout/get_actualheight/)) และค่าจริงของแกน ([IAxis::get_ActualMaxValue](../iaxis/get_actualmaxvalue/), [IAxis::get_ActualMinValue](../iaxis/get_actualminvalue/), [IAxis::get_ActualMajorUnit](../iaxis/get_actualmajorunit/), [IAxis::get_ActualMinorUnit](../iaxis/get_actualminorunit/), [IAxis::get_ActualMajorUnitScale](../iaxis/get_actualmajorunitscale/), [IAxis::get_ActualMinorUnitScale](../iaxis/get_actualminorunitscale/)) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวน weak reference. ไม่ควรเรียกโดยตรง; แทนที่ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวน weak reference. ไม่ควรเรียกโดยตรง; แทนที่ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | บันทึกเนื้อหาของ [Shape](../../aspose.slides/shape/) เป็นไฟล์ SVG |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | บันทึกเนื้อหาของ [Shape](../../aspose.slides/shape/) เป็นไฟล์ SVG |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [IGraphicalObject](../../aspose.slides/igraphicalobject/)
* คลาส [IFormattedTextContainer](../iformattedtextcontainer/)
* คลาส [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable/)
* เนมสเปซ [Aspose::Slides::Charts](../)
* ไลบรารี [Aspose.Slides](../../)