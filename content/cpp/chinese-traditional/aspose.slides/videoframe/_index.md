---
title: VideoFrame
second_title: Aspose.Slides C++ API 參考
description: 表示投影片上的影片剪輯。
type: docs
weight: 5552
url: /zh-hant/aspose.slides/videoframe/
---
## VideoFrame 類別

表示投影片上的視訊剪輯。

```cpp
class VideoFrame : public Aspose::Slides::PictureFrame,
                   public Aspose::Slides::IVideoFrame
```

## 方法

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | 如果不存在則新增佔位符，並將佔位符屬性設定為指定的佔位符。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../geometryshape/createshapeelements/)() override | 建立並回傳形狀元素的陣列。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../geometryshape/get_adjustment/)(**int32_t**) override | 在指定索引處回傳形狀的調整值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../geometryshape/get_adjustments/)() override | 回傳形狀調整值的集合。唯讀 [IAdjustValueCollection](../iadjustvaluecollection/)。 |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | 回傳與形狀關聯的替代文字。唯讀 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | 回傳與形狀關聯的替代文字標題。唯讀 [System::String](../../system/string/)。 |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | 屬性指定形狀在黑白顯示模式下的呈現方式。唯讀 [Slides::BlackWhiteMode](../blackwhitemode/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ICaptionsCollection](../icaptionscollection/)\> [get_CaptionTracks](./get_captiontracks/)() override | 取得與影片框架關聯的隱藏式字幕集合。此屬性為唯讀，回傳包含所有字幕軌道的 [ICaptionsCollection](../icaptionscollection/)。 |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | 回傳形狀的連接點數量。唯讀 **int32_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | 回傳形狀的自訂資料。唯讀 [ICustomData](../icustomdata/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | 回傳包含套用於形狀之像素效果的 [EffectFormat](../effectformat/) 物件。註：對於沒有效果屬性的某些形狀類型，可能回傳 null。唯讀 [IEffectFormat](../ieffectformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IVideo](../ivideo/)\> [get_EmbeddedVideo](./get_embeddedvideo/)() override | 回傳內嵌影片物件。唯讀 [IVideo](../ivideo/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | 回傳包含形狀填充格式屬性的 [FillFormat](../fillformat/) 物件。註：對於沒有填充屬性的某些形狀類型，可能回傳 null。唯讀 [IFillFormat](../ifillformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | 回傳形狀框架的屬性。唯讀 [IShapeFrame](../ishapeframe/)。 |
| **bool** [get_FullScreenMode](./get_fullscreenmode/)() override | 判斷影片是否以全螢幕模式顯示。唯讀 **bool**。 |
| **float** [get_Height](../shape/get_height/)() override | 取得形狀的高度（以點為單位）。唯讀 **float**。 |
| **bool** [get_Hidden](../shape/get_hidden/)() override | 判斷形狀是否被隱藏。唯讀 **bool**。 |
| **bool** [get_HideAtShowing](./get_hideatshowing/)() override | 判斷 [VideoFrame](./) 是否被隱藏。唯讀 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | 回傳已定義的滑鼠點擊超連結。唯讀 [IHyperlink](../ihyperlink/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | 回傳超連結管理器。唯讀 [IHyperlinkManager](../ihyperlinkmanager/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | 回傳已定義的滑鼠懸停超連結。唯讀 [IHyperlink](../ihyperlink/)。 |
| **bool** [get_IsCameo](../pictureframe/get_iscameo/)() | 判斷 [PictureFrame](../pictureframe/) 是否為 Cameo 物件。唯讀 **bool**。 |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | 取得「標記為裝飾」選項，讀寫 **bool**。 |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | 判斷形狀是否已群組。唯讀 **bool**。 |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | 判斷形狀是否為 TextHolder_PPT。唯讀 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | 回傳包含形狀線條格式屬性的 [LineFormat](../lineformat/) 物件。註：對於沒有線條屬性的某些形狀類型，可能回傳 null。唯讀 [ILineFormat](../ilineformat/)。 |
| [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() override | 回傳連結至 [VideoFrame](./) 的影片檔案名稱。唯讀 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | 回傳形狀的名稱。不得為 null，必要時使用空字串。唯讀 [System::String](../../system/string/)。 |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | 回傳在投影片範圍內唯一且在形狀生命期間保持不變的識別碼，讓 PowerPoint 或互操作程式碼能從文件任何位置可靠地參照形狀。唯讀 **uint32_t**。另請參閱 [Shape::get_UniqueId](../shape/get_uniqueid/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | 如果形狀已群組，回傳父層 [GroupShape](../groupshape/) 物件；否則回傳 null。唯讀 [IGroupShape](../igroupshape/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_PictureFormat](../pictureframe/get_pictureformat/)() override | 回傳圖片框的 [PictureFillFormat](../picturefillformat/) 物件。唯讀 [IPictureFillFormat](../ipicturefillformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrameLock](../ipictureframelock/)\> [get_PictureFrameLock](../pictureframe/get_pictureframelock/)() override | 回傳形狀的鎖定設定。唯讀 [IPictureFrameLock](../ipictureframelock/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | 回傳形狀的佔位符。如果形狀沒有佔位符則回傳 null。唯讀 [IPlaceholder](../iplaceholder/)。 |
| **bool** [get_PlayLoopMode](./get_playloopmode/)() override | 判斷影片是否循環播放。唯讀 **bool**。 |
| [VideoPlayModePreset](../videoplaymodepreset/) [get_PlayMode](./get_playmode/)() override | 回傳影片播放模式。唯讀 [VideoPlayModePreset](../videoplaymodepreset/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | 回傳投影片的父層簡報。唯讀 [IPresentation](../ipresentation/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | 回傳原始形狀框架的屬性。唯讀 [IShapeFrame](../ishapeframe/)。 |
| **float** [get_RelativeScaleHeight](../pictureframe/get_relativescaleheight/)() override | 回傳圖片框高度縮放比例（相對於原始圖片大小）。數值 1.0 對應 100%。唯讀 **float**。 |
| **float** [get_RelativeScaleWidth](../pictureframe/get_relativescalewidth/)() override | 回傳圖片框寬度縮放比例（相對於原始圖片大小）。數值 1.0 對應 100%。唯讀 **float**。 |
| **bool** [get_RewindVideo](./get_rewindvideo/)() override | 判斷影片是否在播放結束後自動倒回起始。唯讀 **bool**。 |
| **float** [get_Rotation](../shape/get_rotation/)() override | 回傳指定形狀繞 Z 軸旋轉的角度（度）。正值表示順時針旋轉，負值表示逆時針旋轉。唯讀 **float**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | 回傳形狀的鎖定設定。唯讀 [IBaseShapeLock](../ibaseshapelock/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../geometryshape/get_shapestyle/)() override | 回傳形狀的樣式物件。唯讀 [IShapeStyle](../ishapestyle/)。 |
| [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../pictureframe/get_shapetype/)() override |  |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | 回傳形狀的父層投影片。唯讀 [IBaseSlide](../ibaseslide/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | 回傳形狀的 [ThreeDFormat](../threedformat/) 3D 效果屬性物件。註：對於沒有 3D 屬性的某些形狀類型，可能回傳 null。唯讀 [IThreeDFormat](../ithreedformat/)。 |
| **float** [get_TrimFromEnd](./get_trimfromend/)() override | 剪裁結束 [ms] |
| **float** [get_TrimFromStart](./get_trimfromstart/)() override | 剪裁開始 [ms] |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | 回傳供外掛或其他程式碼使用的內部簡報範圍識別碼。由於此值可被使用者或程式重新指派，不能視為永久唯一鍵。唯讀 **uint32_t**。另請參閱 [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)。 |
| [AudioVolumeMode](../audiovolumemode/) [get_Volume](./get_volume/)() override | 回傳音訊音量。唯讀 [AudioVolumeMode](../audiovolumemode/)。 |
| **float** [get_Width](../shape/get_width/)() override | 取得形狀的寬度（以點為單位）。唯讀 **float**。 |
| **float** [get_X](../shape/get_x/)() override | 取得形狀左上角的 X 座標（以點為單位）。唯讀 **float**。 |
| **float** [get_Y](../shape/get_y/)() override | 取得形狀左上角的 Y 座標（以點為單位）。唯讀 **float**。 |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | 回傳形狀在 Z 序中的位置。Shapes[0] 為 Z 序最靠後的形狀，Shapes[Shapes.Count - 1] 為最前面的形狀。唯讀 **int32_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | 回傳基本佔位符形狀（從版面配置與/或母片中繼承的形狀）。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../geometryshape/getgeometrypaths/)() override | 回傳幾何形狀路徑的副本。座標相對於形狀的左上角。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | 回傳形狀縮圖。預設使用 [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) 形狀縮圖邊界類型。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | 回傳形狀縮圖。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | 取得根據渲染內容計算的形狀視覺邊界。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。相當於 C# 的 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂類型的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構函式。實際上不複製任何東西，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 賦值運算子。實際上不複製任何東西，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 針對字串與 nullptr 情況的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 針對字串情況的特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數下降指定值。 |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | 定義此形狀不是佔位符。 |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | 設定與形狀關聯的替代文字。寫入 [System::String](../../system/string/)。 |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | 設定與形狀關聯的替代文字標題。寫入 [System::String](../../system/string/)。 |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | 屬性指定形狀在黑白顯示模式下的呈現方式。寫入 [Slides::BlackWhiteMode](../blackwhitemode/)。 |
| void [set_EmbeddedVideo](./set_embeddedvideo/)([System::SharedPtr](../../system/sharedptr/)\<[IVideo](../ivideo/)\>) override | 設定內嵌影片物件。寫入 [IVideo](../ivideo/)。 |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | 設定形狀框架的屬性。寫入 [IShapeFrame](../ishapeframe/)。 |
| void [set_FullScreenMode](./set_fullscreenmode/)(**bool**) override | 判斷影片是否以全螢幕模式顯示。寫入 **bool**。 |
| void [set_Height](../shape/set_height/)(**float**) override | 設定形狀的高度（以點為單位）。寫入 **float**。 |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | 判斷形狀是否被隱藏。寫入 **bool**。 |
| void [set_HideAtShowing](./set_hideatshowing/)(**bool**) override | 判斷 [VideoFrame](./) 是否被隱藏。寫入 **bool**。 |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | 設定滑鼠點擊的超連結。寫入 [IHyperlink](../ihyperlink/)。 |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | 設定滑鼠懸停的超連結。寫入 [IHyperlink](../ihyperlink/)。 |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | 設定「標記為裝飾」選項，讀寫 **bool**。 |
| void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) override | 設定連結至 [VideoFrame](./) 的影片檔案名稱。寫入 [System::String](../../system/string/)。 |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | 設定形狀名稱。不得為 null，必要時使用空字串。寫入 [System::String](../../system/string/)。 |
| void [set_PlayLoopMode](./set_playloopmode/)(**bool**) override | 判斷影片是否循環播放。寫入 **bool**。 |
| void [set_PlayMode](./set_playmode/)([VideoPlayModePreset](../videoplaymodepreset/)) override | 設定影片播放模式。寫入 [VideoPlayModePreset](../videoplaymodepreset/)。 |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | 設定原始形狀框架的屬性。寫入 [IShapeFrame](../ishapeframe/)。 |
| void [set_RelativeScaleHeight](../pictureframe/set_relativescaleheight/)(**float**) override | 設定圖片框高度縮放比例（相對於原始圖片大小）。數值 1.0 對應 100%。寫入 **float**。 |
| void [set_RelativeScaleWidth](../pictureframe/set_relativescalewidth/)(**float**) override | 設定圖片框寬度縮放比例（相對於原始圖片大小）。數值 1.0 對應 100%。寫入 **float**。 |
| void [set_RewindVideo](./set_rewindvideo/)(**bool**) override | 判斷影片是否在播放結束後自動倒回起始。寫入 **bool**。 |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | 設定指定形狀繞 Z 軸旋轉的角度（度）。正值表示順時針旋轉，負值表示逆時針旋轉。寫入 **float**。 |
| void [set_ShapeType](../pictureframe/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) override |  |
| void [set_TrimFromEnd](./set_trimfromend/)(**float**) override | 剪裁結束 [ms] |
| void [set_TrimFromStart](./set_trimfromstart/)(**float**) override | 剪裁開始 [ms] |
| void [set_Volume](./set_volume/)([AudioVolumeMode](../audiovolumemode/)) override | 設定音訊音量。寫入 [AudioVolumeMode](../audiovolumemode/)。 |
| void [set_Width](../shape/set_width/)(**float**) override | 設定形狀的寬度（以點為單位）。寫入 **float**。 |
| void [set_X](../shape/set_x/)(**float**) override | 設定形狀左上角的 X 座標（以點為單位）。寫入 **float**。 |
| void [set_Y](../shape/set_y/)(**float**) override | 設定形狀左上角的 Y 座標（以點為單位）。寫入 **float**。 |
| void [SetGeometryPath](../geometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) override | 從 [IGeometryPath](../igeometrypath/) 物件更新形狀幾何。座標必須相對於形狀的左上角。將形狀類型 ([ShapeType](../shapetype/)) 變更為 [ShapeType::Custom](../shapetype/)。 |
| void [SetGeometryPaths](../geometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) override | 從 [IGeometryPath](../igeometrypath/) 陣列更新形狀幾何。座標必須相對於形狀的左上角。將形狀類型 ([ShapeType](../shapetype/)) 變更為 [ShapeType::Custom](../shapetype/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用自訂物件轉為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | 將 [Shape](../shape/) 內容另存為 SVG 檔案。 |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | 將 [Shape](../shape/) 內容另存為 SVG 檔案。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 參見

* 類別 [PictureFrame](../pictureframe/)
* 類別 [IVideoFrame](../ivideoframe/)
* 命名空間 [Aspose::Slides](../)
* 函式庫 [Aspose.Slides](../../)