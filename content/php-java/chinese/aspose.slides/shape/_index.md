---
title: Shape
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/shape/
---
## Shape 类

  表示幻灯片上的一个形状。
 
### addPlaceholder {#addPlaceholder}

| 名称 | 描述 |
| --- | --- |
| addPlaceholder ([Placeholder](../placeholder)) | 如果不存在，则添加新的占位符并将占位符属性设置为指定的占位符。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| placeholderToCopyFrom | [Placeholder](../placeholder) | 用于复制内容的占位符。 |

**返回值:**
[Placeholder](../placeholder)

---


### getAlternativeText {#getAlternativeText}

| 名称 | 描述 |
| --- | --- |
| getAlternativeText () | 返回或设置与形状关联的替代文本。读/写 String。 |

**返回值:**
String

---


### getAlternativeTextTitle {#getAlternativeTextTitle}

| 名称 | 描述 |
| --- | --- |
| getAlternativeTextTitle () | 返回或设置与形状关联的替代文本标题。读/写 String。 |

**返回值:**
String

---


### getBasePlaceholder {#getBasePlaceholder}

| 名称 | 描述 |
| --- | --- |
| getBasePlaceholder () | 返回基本占位符形状（布局和/或母版幻灯片中的形状，当前形状从其继承）。如果当前形状未继承，则返回 null。 |

**返回值:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### getBlackWhiteMode {#getBlackWhiteMode}

| 名称 | 描述 |
| --- | --- |
| getBlackWhiteMode () | 属性指定形状在黑白显示模式下的渲染方式。读/写 BlackWhiteMode。 |

**返回值:**
byte

---


### getConnectionSiteCount {#getConnectionSiteCount}

| 名称 | 描述 |
| --- | --- |
| getConnectionSiteCount () | 返回形状上的连接点数量。只读 int。 |

**返回值:**
int

---


### getCustomData {#getCustomData}

| 名称 | 描述 |
| --- | --- |
| getCustomData () | 返回形状的自定义数据。只读 ICustomData。 |

**返回值:**
[CustomData](../customdata)

---


### getEffectFormat {#getEffectFormat}

| 名称 | 描述 |
| --- | --- |
| getEffectFormat () | 返回包含形状像素效果的 EffectFormat 对象。注意：对于某些没有效果属性的形状可能返回 null。只读 IEffectFormat。 |

**返回值:**
[EffectFormat](../effectformat)

---


### getFillFormat {#getFillFormat}

| 名称 | 描述 |
| --- | --- |
| getFillFormat () | 返回包含形状填充属性的 FillFormat 对象。注意：对于某些没有填充属性的形状可能返回 null。只读 IFillFormat。 |

**返回值:**
[FillFormat](../fillformat)

---


### getFrame {#getFrame}

| 名称 | 描述 |
| --- | --- |
| getFrame () | 返回或设置形状框架的属性。读/写 IShapeFrame。返回的 IShapeFrame 实例的每个属性值均已定义（不是 NaN 或 NotDefined）。分配的 IShapeFrame 实例的每个属性值必须已定义（不是 NaN 或 NotDefined）。可以为 RawFrame 实例属性设置未定义值。 |

**返回值:**
[ShapeFrame](../shapeframe)

---


### getHeight {#getHeight}

| 名称 | 描述 |
| --- | --- |
| getHeight () | 获取或设置形状的高度，单位为点。读/写 float。返回值始终已定义且不会为 Float.NaN。分配的值也必须已定义；仅对 RawFrame 实例的属性分配 Float.NaN。 |

**返回值:**
float

---


### getHidden {#getHidden}

| 名称 | 描述 |
| --- | --- |
| getHidden () | 确定形状是否隐藏。读/写 boolean。 |

**返回值:**
boolean

---


### getHyperlinkClick {#getHyperlinkClick}

| 名称 | 描述 |
| --- | --- |
| getHyperlinkClick () | 返回或设置鼠标单击时定义的超链接。读/写 IHyperlink。 |

**返回值:**
[Hyperlink](../hyperlink)

---


### getHyperlinkManager {#getHyperlinkManager}

| 名称 | 描述 |
| --- | --- |
| getHyperlinkManager () | 返回超链接管理器。只读 IHyperlinkManager。 |

**返回值:**
[HyperlinkManager](../hyperlinkmanager)

---


### getHyperlinkMouseOver {#getHyperlinkMouseOver}

| 名称 | 描述 |
| --- | --- |
| getHyperlinkMouseOver () | 返回或设置鼠标悬停时定义的超链接。读/写 IHyperlink。 |

**返回值:**
[Hyperlink](../hyperlink)

---


### getImage {#getImage}

| 名称 | 描述 |
| --- | --- |
| getImage () | 返回形状缩略图。默认使用 ShapeThumbnailBounds.Shape 形状缩略图边界类型。 |

**返回值:**
IImage

---


### getImage {#getImage}

| 名称 | 描述 |
| --- | --- |
| getImage (int, float, float) | 返回形状缩略图。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| bounds | int | 形状缩略图边界类型。 |
| scaleX | float | X 方向比例 |
| scaleY | float | Y 方向比例 |

**返回值:**
IImage

---


### getLineFormat {#getLineFormat}

| 名称 | 描述 |
| --- | --- |
| getLineFormat () | 返回包含形状线条属性的 LineFormat 对象。注意：对于某些没有线条属性的形状可能返回 null。只读 ILineFormat。 |

**返回值:**
[LineFormat](../lineformat)

---


### getName {#getName}

| 名称 | 描述 |
| --- | --- |
| getName () | 返回或设置形状的名称。必须非 null，如有需要可使用空字符串。读/写 String。 |

**返回值:**
String

---


### getOfficeInteropShapeId {#getOfficeInteropShapeId}

| 名称 | 描述 |
| --- | --- |
| getOfficeInteropShapeId () | 返回在幻灯片范围内唯一且在形状生命周期内保持不变的标识符，供 PowerPoint 或互操作代码可靠引用形状。只读 long。另请参见 #getUniqueId。 |

**返回值:**
long

---


### getParentGroup {#getParentGroup}

| 名称 | 描述 |
| --- | --- |
| getParentGroup () | 如果形状已分组，则返回父级 GroupShape 对象；否则返回 null。只读 IGroupShape。属性 #isGrouped 决定形状是否分组。 |

**返回值:**
[GroupShape](../groupshape)

---


### getPlaceholder {#getPlaceholder}

| 名称 | 描述 |
| --- | --- |
| getPlaceholder () | 返回形状的占位符。如果形状没有占位符，则返回 null。只读 IPlaceholder。 |

**返回值:**
[Placeholder](../placeholder)

---


### getPresentation {#getPresentation}

| 名称 | 描述 |
| --- | --- |
| getPresentation () | 返回幻灯片的父级演示文稿。只读 IPresentation。 |

**返回值:**
[Presentation](../presentation)

---


### getRawFrame {#getRawFrame}

| 名称 | 描述 |
| --- | --- |
| getRawFrame () | 返回或设置原始形状框架的属性。读/写 IShapeFrame。 |

**返回值:**
[ShapeFrame](../shapeframe)

---


### getRotation {#getRotation}

| 名称 | 描述 |
| --- | --- |
| getRotation () | 返回或设置形状围绕 z 轴旋转的角度（度）。正值表示顺时针旋转，负值表示逆时针旋转。读/写 float。返回值始终已定义（不是 Float.NaN）。分配的值必须已定义（不是 Float.NaN）。可以为 RawFrame 实例属性设置未定义值。 |

**返回值:**
float

---


### getShapeLock {#getShapeLock}

| 名称 | 描述 |
| --- | --- |
| getShapeLock () | 返回形状的锁定信息。只读 IBaseShapeLock。 |

**返回值:**
[GraphicalObjectLock](../graphicalobjectlock), [ConnectorLock](../connectorlock), [AutoShapeLock](../autoshapelock), [PictureFrameLock](../pictureframelock), [BaseShapeLock](../baseshapelock), [GroupShapeLock](../groupshapelock)

---


### getSlide {#getSlide}

| 名称 | 描述 |
| --- | --- |
| getSlide () | 返回形状所属的父幻灯片。只读 IBaseSlide。 |

**返回值:**
[MasterHandoutSlide](../masterhandoutslide), [BaseSlide](../baseslide), [LayoutSlide](../layoutslide), [Slide](../slide), [MasterSlide](../masterslide), [NotesSlide](../notesslide), [MasterNotesSlide](../masternotesslide)

---


### getThreeDFormat {#getThreeDFormat}

| 名称 | 描述 |
| --- | --- |
| getThreeDFormat () | 返回形状的 ThreeDFormat 对象，其中包含 3D 效果属性。注意：对于某些没有 3D 属性的形状可能返回 null。只读 IThreeDFormat。 |

**返回值:**
[ThreeDFormat](../threedformat)

---


### getUniqueId {#getUniqueId}

| 名称 | 描述 |
| --- | --- |
| getUniqueId () | 返回内部的、演示文稿范围的标识符，供插件或其他代码使用。由于该值可能被用户或程序重新分配，不能视为持久唯一键。只读 long。另请参见 #getOfficeInteropShapeId。 |

**返回值:**
long

---


### getVisualBounds {#getVisualBounds}

| 名称 | 描述 |
| --- | --- |
| getVisualBounds () | 获取形状从渲染内容计算得出的可视边界。 |

**返回值:**
Rectangle2D.Float

---


### getWidth {#getWidth}

| 名称 | 描述 |
| --- | --- |
| getWidth () | 获取或设置形状的宽度，单位为点。读/写 float。返回值始终已定义且不会为 Float.NaN。分配的值也必须已定义；仅对 RawFrame 实例的属性分配 Float.NaN。 |

**返回值:**
float

---


### getX {#getX}

| 名称 | 描述 |
| --- | --- |
| getX () | 获取或设置形状左上角的 X 坐标，单位为点。读/写 float。返回值始终已定义且不会为 Float.NaN。分配的值也必须已定义；仅对 RawFrame 实例的属性分配 Float.NaN。 |

**返回值:**
float

---


### getY {#getY}

| 名称 | 描述 |
| --- | --- |
| getY () | 获取或设置形状左上角的 Y 坐标，单位为点。读/写 float。返回值始终已定义且不会为 Float.NaN。分配的值也必须已定义；仅对 RawFrame 实例的属性分配 Float.NaN。 |

**返回值:**
float

---


### getZOrderPosition {#getZOrderPosition}

| 名称 | 描述 |
| --- | --- |
| getZOrderPosition () | 返回形状在 Z 顺序中的位置。Shapes[0] 为 Z 顺序最底部的形状，Shapes[Shapes.Count - 1] 为最前面的形状。只读 int。 |

**返回值:**
int

---


### isDecorative {#isDecorative}

| 名称 | 描述 |
| --- | --- |
| isDecorative () | 获取或设置 “标记为装饰性” 选项。读/写 boolean。 |

**返回值:**
boolean

---


### isGrouped {#isGrouped}

| 名称 | 描述 |
| --- | --- |
| isGrouped () | 确定形状是否已分组。只读 boolean。属性 #getParentGroup 在形状已分组时返回父 GroupShape 对象。 |

**返回值:**
boolean

---


### isTextHolder {#isTextHolder}

| 名称 | 描述 |
| --- | --- |
| isTextHolder () | 确定形状是否为 TextHolder_PPT。只读 boolean。 |

**返回值:**
boolean

---


### removePlaceholder {#removePlaceholder}

| 名称 | 描述 |
| --- | --- |
| removePlaceholder () | 定义此形状不是占位符。 |

**返回值:**
void

---


### setAlternativeText {#setAlternativeText}

| 名称 | 描述 |
| --- | --- |
| setAlternativeText (String) | 返回或设置与形状关联的替代文本。读/写 String。 |

**返回值:**
void

---


### setAlternativeTextTitle {#setAlternativeTextTitle}

| 名称 | 描述 |
| --- | --- |
| setAlternativeTextTitle (String) | 返回或设置与形状关联的替代文本标题。读/写 String。 |

**返回值:**
void

---


### setBlackWhiteMode {#setBlackWhiteMode}

| 名称 | 描述 |
| --- | --- |
| setBlackWhiteMode (byte) | 属性指定形状在黑白显示模式下的渲染方式。读/写 BlackWhiteMode。 |

**返回值:**
void

---


### setDecorative {#setDecorative}

| 名称 | 描述 |
| --- | --- |
| setDecorative (boolean) | 获取或设置 “标记为装饰性” 选项。读/写 boolean。 |

**返回值:**
void

---


### setFrame {#setFrame}

| 名称 | 描述 |
| --- | --- |
| setFrame ([ShapeFrame](../shapeframe)) | 返回或设置形状框架的属性。读/写 IShapeFrame。返回的 IShapeFrame 实例的每个属性值均已定义（不是 NaN 或 NotDefined）。分配的 IShapeFrame 实例的每个属性值必须已定义（不是 NaN 或 NotDefined）。可以为 RawFrame 实例属性设置未定义值。 |

**返回值:**
void

---


### setHeight {#setHeight}

| 名称 | 描述 |
| --- | --- |
| setHeight (float) | 获取或设置形状的高度，单位为点。读/写 float。返回值始终已定义且不会为 Float.NaN。分配的值也必须已定义；仅对 RawFrame 实例的属性分配 Float.NaN。 |

**返回值:**
void

---


### setHidden {#setHidden}

| 名称 | 描述 |
| --- | --- |
| setHidden (boolean) | 确定形状是否隐藏。读/写 boolean。 |

**返回值:**
void

---


### setHyperlinkClick {#setHyperlinkClick}

| 名称 | 描述 |
| --- | --- |
| setHyperlinkClick ([Hyperlink](../hyperlink)) | 返回或设置鼠标单击时定义的超链接。读/写 IHyperlink。 |

**返回值:**
void

---


### setHyperlinkMouseOver {#setHyperlinkMouseOver}

| 名称 | 描述 |
| --- | --- |
| setHyperlinkMouseOver ([Hyperlink](../hyperlink)) | 返回或设置鼠标悬停时定义的超链接。读/写 IHyperlink。 |

**返回值:**
void

---


### setName {#setName}

| 名称 | 描述 |
| --- | --- |
| setName (String) | 返回或设置形状的名称。必须非 null，如有需要可使用空字符串。读/写 String。 |

**返回值:**
void

---


### setRawFrame {#setRawFrame}

| 名称 | 描述 |
| --- | --- |
| setRawFrame ([ShapeFrame](../shapeframe)) | 返回或设置原始形状框架的属性。读/写 IShapeFrame。 |

**返回值:**
void

---


### setRotation {#setRotation}

| 名称 | 描述 |
| --- | --- |
| setRotation (float) | 返回或设置形状围绕 z 轴旋转的角度（度）。正值表示顺时针旋转，负值表示逆时针旋转。读/写 float。返回值始终已定义（不是 Float.NaN）。分配的值必须已定义（不是 Float.NaN）。可以为 RawFrame 实例属性设置未定义值。 |

**返回值:**
void

---


### setWidth {#setWidth}

| 名称 | 描述 |
| --- | --- |
| setWidth (float) | 获取或设置形状的宽度，单位为点。读/写 float。返回值始终已定义且不会为 Float.NaN。分配的值也必须已定义；仅对 RawFrame 实例的属性分配 Float.NaN。 |

**返回值:**
void

---


### setX {#setX}

| 名称 | 描述 |
| --- | --- |
| setX (float) | 获取或设置形状左上角的 X 坐标，单位为点。读/写 float。返回值始终已定义且不会为 Float.NaN。分配的值也必须已定义；仅对 RawFrame 实例的属性分配 Float.NaN。 |

**返回值:**
void

---


### setY {#setY}

| 名称 | 描述 |
| --- | --- |
| setY (float) | 获取或设置形状左上角的 Y 坐标，单位为点。读/写 float。返回值始终已定义且不会为 Float.NaN。分配的值也必须已定义；仅对 RawFrame 实例的属性分配 Float.NaN。 |

**返回值:**
void

---


### writeAsSvg {#writeAsSvg}

| 名称 | 描述 |
| --- | --- |
| writeAsSvg (OutputStream) | 将 Shape 内容保存为 SVG 文件。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| stream | OutputStream | 目标流 |

**返回值:**
void

---


### writeAsSvg {#writeAsSvg}

| 名称 | 描述 |
| --- | --- |
| writeAsSvg (OutputStream, [SVGOptions](../svgoptions)) | 将 Shape 内容保存为 SVG 文件。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| stream | OutputStream | 目标流 |
| svgOptions | [SVGOptions](../svgoptions) | SVG 生成选项 |

**返回值:**
void

---