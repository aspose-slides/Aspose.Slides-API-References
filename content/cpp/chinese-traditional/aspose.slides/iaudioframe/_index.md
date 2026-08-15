---
title: IAudioFrame
second_title: Aspose.Slides C++ API 參考
description: 表示投影片上的音訊剪輯。
type: docs
weight: 1353
url: /zh-hant/aspose.slides/iaudioframe/
---
## IAudioFrame 類別


表示投影片上的音訊剪輯。

```cpp
class IAudioFrame : public virtual Aspose::Slides::IPictureFrame
```

## 方法

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | 如果不存在則新增佔位元件，並將佔位元件屬性設定為指定的佔位元件。 |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../igeometryshape/createshapeelements/)() | 建立並傳回形狀元素的陣列。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../igeometryshape/get_adjustment/)(**int32_t**) | 傳回指定索引處的形狀調整值。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../igeometryshape/get_adjustments/)() | 傳回形狀調整值的集合。唯讀 [IAdjustValueCollection](../iadjustvaluecollection/)。 |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | 傳回與形狀關聯的替代文字。讀取 [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | 傳回與形狀關聯的替代文字標題。讀取 [System::String](../../system/string/)。 |
| virtual **int32_t** [get_AudioCdEndTrack](./get_audiocdendtrack/)() | 傳回最後的軌道索引。讀取 **int32_t**。 |
| virtual **int32_t** [get_AudioCdEndTrackTime](./get_audiocdendtracktime/)() | 傳回最後的軌道時間。讀取 **int32_t**。 |
| virtual **int32_t** [get_AudioCdStartTrack](./get_audiocdstarttrack/)() | 傳回開始的軌道索引。讀取 **int32_t**。 |
| virtual **int32_t** [get_AudioCdStartTrackTime](./get_audiocdstarttracktime/)() | 傳回開始的軌道時間。讀取 **int32_t**。 |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | 屬性指定形狀在黑白顯示模式下的呈現方式。讀取 [Slides::BlackWhiteMode](../blackwhitemode/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICaptionsCollection](../icaptionscollection/)\> [get_CaptionTracks](./get_captiontracks/)() | 取得與音訊框架關聯的隱藏式字幕集合。此屬性為唯讀，傳回包含所有字幕軌道的 [ICaptionsCollection](../icaptionscollection/)。 |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | 傳回形狀的連接點數量。唯讀 **int32_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | 傳回形狀的自訂資料。唯讀 [ICustomData](../icustomdata/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | 傳回包含套用於形狀的像素效果的 [EffectFormat](../effectformat/) 物件。唯讀 [IEffectFormat](../ieffectformat/)。 |
| virtual **bool** [get_Embedded](./get_embedded/)() | 判斷聲音是否嵌入簡報。唯讀 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_EmbeddedAudio](./get_embeddedaudio/)() | 傳回嵌入的音訊物件。讀取 [IAudio](../iaudio/)。 |
| virtual **float** [get_FadeInDuration](./get_fadeinduration/)() | 指定媒體初始淡入的時間長度（毫秒）。讀取 **float**。 |
| virtual **float** [get_FadeOutDuration](./get_fadeoutduration/)() | 指定媒體結束淡出的時間長度（毫秒）。讀取 **float**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | 傳回包含形狀填充格式屬性的 [FillFormat](../fillformat/) 物件。唯讀 [IFillFormat](../ifillformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | 傳回形狀框架的屬性。讀取 [IShapeFrame](../ishapeframe/)。 |
| virtual **float** [get_Height](../ishape/get_height/)() | 取得形狀的高度（以點為單位）。讀取 **float**。 |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | 判斷形狀是否隱藏。讀取 **bool**。 |
| virtual **bool** [get_HideAtShowing](./get_hideatshowing/)() | 判斷 [AudioFrame](../audioframe/) 是否隱藏。讀取 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | 傳回滑鼠點擊時的超連結。讀取 [IHyperlink](../ihyperlink/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | 超連結管理器。唯讀 [IHyperlinkManager](../ihyperlinkmanager/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | 傳回滑鼠懸停時的超連結。讀取 [IHyperlink](../ihyperlink/)。 |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | 取得「標記為裝飾」選項。讀寫 **bool**。 |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | 判斷形狀是否已群組。唯讀 **bool**。 |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | 判斷形狀是否為 TextHolder。唯讀 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | 傳回包含形狀線條格式屬性的 [LineFormat](../lineformat/) 物件。唯讀 [ILineFormat](../ilineformat/)。 |
| virtual [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() | 傳回連結至 [AudioFrame](../audioframe/) 的音訊檔案名稱。讀取 [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | 傳回形狀的名稱。讀取 [System::String](../../system/string/)。 |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | 傳回在投影片範圍內唯一的識別碼，於形狀生命週期內保持不變，讓 PowerPoint 或互通程式碼能從文件任何位置可靠地參考該形狀。唯讀 **uint32_t**。另請參閱 [IShape::get_UniqueId](../ishape/get_uniqueid/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | 如果形狀已群組，傳回父 [GroupShape](../groupshape/) 物件；否則傳回 null。唯讀 [IGroupShape](../igroupshape/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_PictureFormat](../ipictureframe/get_pictureformat/)() | 傳回圖片框架的 [PictureFillFormat](../picturefillformat/) 物件。唯讀 [IPictureFillFormat](../ipicturefillformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrameLock](../ipictureframelock/)\> [get_PictureFrameLock](../ipictureframe/get_pictureframelock/)() | 傳回 [PictureFrame](../pictureframe/) 的鎖定。唯讀 [IPictureFrameLock](../ipictureframelock/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | 傳回形狀的佔位元件。唯讀 [IPlaceholder](../iplaceholder/)。 |
| virtual **bool** [get_PlayAcrossSlides](./get_playacrossslides/)() | 判斷音訊是否跨投影片播放。讀取 **bool**。 |
| virtual **bool** [get_PlayLoopMode](./get_playloopmode/)() | 判斷音訊是否重複播放。讀取 **bool**。 |
| virtual [AudioPlayModePreset](../audioplaymodepreset/) [get_PlayMode](./get_playmode/)() | 傳回音訊播放模式。讀取 [AudioPlayModePreset](../audioplaymodepreset/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | 傳回簡報。唯讀 [IPresentation](../ipresentation/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | 傳回原始形狀框架的屬性。讀取 [IShapeFrame](../ishapeframe/)。 |
| virtual **float** [get_RelativeScaleHeight](../ipictureframe/get_relativescaleheight/)() | 傳回圖片框架高度的比例（相對於原始圖片大小）。值 1.0 代表 100%。讀取 **float**。 |
| virtual **float** [get_RelativeScaleWidth](../ipictureframe/get_relativescalewidth/)() | 傳回圖片框架寬度的比例（相對於原始圖片大小）。值 1.0 代表 100%。讀取 **float**。 |
| virtual **bool** [get_RewindAudio](./get_rewindaudio/)() | 判斷音訊在播放完畢後是否自動倒回至開始。讀取 **bool**。 |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | 傳回指定形狀繞 Z 軸旋轉的角度（度），正值表示順時針旋轉，負值表示逆時針旋轉。讀取 **float**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | 傳回形狀的鎖定。唯讀 [IBaseShapeLock](../ibaseshapelock/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../igeometryshape/get_shapestyle/)() | 傳回形狀的樣式物件。唯讀 [IShapeStyle](../ishapestyle/)。 |
| virtual [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../igeometryshape/get_shapetype/)() | 傳回幾何預設類型。注意：變更值時，所有調整值將重設為預設值。讀取 [Slides::ShapeType](../shapetype/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | 傳回基礎投影片。唯讀 [IBaseSlide](../ibaseslide/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | 傳回包含形狀線條格式屬性的 [ThreeDFormat](../threedformat/) 物件。唯讀 [IThreeDFormat](../ithreedformat/)。 |
| virtual **float** [get_TrimFromEnd](./get_trimfromend/)() | 指定在播放期間從媒體結尾移除的時間長度（毫秒）。讀取 **float**。 |
| virtual **float** [get_TrimFromStart](./get_trimfromstart/)() | 指定在播放期間從媒體開頭移除的時間長度（毫秒）。讀取 **float**。 |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | 傳回內部的、以簡報為範圍的識別碼，供外掛程式或其他程式碼使用。因為此值可能被使用者或程式重新指派，不能視為持久的唯一鍵。唯讀 **uint32_t**。另請參閱 [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)。 |
| virtual [AudioVolumeMode](../audiovolumemode/) [get_Volume](./get_volume/)() | 傳回音訊音量。讀取 [AudioVolumeMode](../audiovolumemode/)。 |
| virtual **float** [get_VolumeValue](./get_volumevalue/)() | 傳回音訊音量（百分比）。讀取 **float**。 |
| virtual **float** [get_Width](../ishape/get_width/)() | 取得形狀的寬度（以點為單位）。讀取 **float**。 |
| virtual **float** [get_X](../ishape/get_x/)() | 取得形狀左上角的 x 座標（以點為單位）。讀取 **float**。 |
| virtual **float** [get_Y](../ishape/get_y/)() | 取得形狀左上角的 y 座標（以點為單位）。讀取 **float**。 |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | 傳回形狀在 Z 序中的位置。Shapes[0] 傳回 Z 序最底層的形狀，Shapes[Shapes.Count - 1] 傳回最前面的形狀。唯讀 **int32_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | 傳回基本的佔位元件形狀（來自版面配置和/或母版投影片，且當前形狀繼承自該形狀）。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件關聯的參考計數資料結構。 |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../igeometryshape/getgeometrypaths/)() | 傳回幾何形狀路徑的副本。座標相對於形狀的左上角。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊功能。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | 傳回形狀縮圖。預設使用 [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) 形狀縮圖邊界類型。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | 傳回形狀縮圖。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。相當於 C# 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 守護物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用複製自訂類型。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構式。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 依參考比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 依參考比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，針對字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，針對字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | 定義此形狀不是佔位元件。 |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | 設定與形狀關聯的替代文字。寫入 [System::String](../../system/string/)。 |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | 設定與形狀關聯的替代文字標題。寫入 [System::String](../../system/string/)。 |
| virtual void [set_AudioCdEndTrack](./set_audiocdendtrack/)(**int32_t**) | 設定最後的軌道索引。寫入 **int32_t**。 |
| virtual void [set_AudioCdEndTrackTime](./set_audiocdendtracktime/)(**int32_t**) | 設定最後的軌道時間。寫入 **int32_t**。 |
| virtual void [set_AudioCdStartTrack](./set_audiocdstarttrack/)(**int32_t**) | 設定開始的軌道索引。寫入 **int32_t**。 |
| virtual void [set_AudioCdStartTrackTime](./set_audiocdstarttracktime/)(**int32_t**) | 設定開始的軌道時間。寫入 **int32_t**。 |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | 屬性指定形狀在黑白顯示模式下的呈現方式。寫入 [Slides::BlackWhiteMode](../blackwhitemode/)。 |
| virtual void [set_EmbeddedAudio](./set_embeddedaudio/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) | 設定嵌入的音訊物件。寫入 [IAudio](../iaudio/)。 |
| virtual void [set_FadeInDuration](./set_fadeinduration/)(**float**) | 指定媒體初始淡入的時間長度（毫秒）。寫入 **float**。 |
| virtual void [set_FadeOutDuration](./set_fadeoutduration/)(**float**) | 指定媒體結束淡出的時間長度（毫秒）。寫入 **float**。 |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | 設定形狀框架的屬性。寫入 [IShapeFrame](../ishapeframe/)。 |
| virtual void [set_Height](../ishape/set_height/)(**float**) | 設定形狀的高度（以點為單位）。寫入 **float**。 |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | 判斷形狀是否隱藏。寫入 **bool**。 |
| virtual void [set_HideAtShowing](./set_hideatshowing/)(**bool**) | 判斷 [AudioFrame](../audioframe/) 是否隱藏。寫入 **bool**。 |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | 設定滑鼠點擊時的超連結。寫入 [IHyperlink](../ihyperlink/)。 |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | 設定滑鼠懸停時的超連結。寫入 [IHyperlink](../ihyperlink/)。 |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | 設定「標記為裝飾」選項。寫入 **bool**。 |
| virtual void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) | 設定連結至 [AudioFrame](../audioframe/) 的音訊檔案名稱。寫入 [System::String](../../system/string/)。 |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | 設定形狀的名稱。寫入 [System::String](../../system/string/)。 |
| virtual void [set_PlayAcrossSlides](./set_playacrossslides/)(**bool**) | 判斷音訊是否跨投影片播放。寫入 **bool**。 |
| virtual void [set_PlayLoopMode](./set_playloopmode/)(**bool**) | 判斷音訊是否重複播放。寫入 **bool**。 |
| virtual void [set_PlayMode](./set_playmode/)([AudioPlayModePreset](../audioplaymodepreset/)) | 設定音訊播放模式。寫入 [AudioPlayModePreset](../audioplaymodepreset/)。 |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | 設定原始形狀框架的屬性。寫入 [IShapeFrame](../ishapeframe/)。 |
| virtual void [set_RelativeScaleHeight](../ipictureframe/set_relativescaleheight/)(**float**) | 設定圖片框架高度的比例（相對於原始圖片大小）。值 1.0 代表 100%。寫入 **float**。 |
| virtual void [set_RelativeScaleWidth](../ipictureframe/set_relativescalewidth/)(**float**) | 設定圖片框架寬度的比例（相對於原始圖片大小）。值 1.0 代表 100%。寫入 **float**。 |
| virtual void [set_RewindAudio](./set_rewindaudio/)(**bool**) | 判斷音訊在播放完畢後是否自動倒回至開始。寫入 **bool**。 |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | 設定指定形狀繞 Z 軸旋轉的角度（度），正值表示順時針旋轉，負值表示逆時針旋轉。寫入 **float**。 |
| virtual void [set_ShapeType](../igeometryshape/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) | 設定幾何預設類型。注意：變更值時，所有調整值將重設為預設值。寫入 [Slides::ShapeType](../shapetype/)。 |
| virtual void [set_TrimFromEnd](./set_trimfromend/)(**float**) | 指定在播放期間從媒體結尾移除的時間長度（毫秒）。寫入 **float**。 |
| virtual void [set_TrimFromStart](./set_trimfromstart/)(**float**) | 指定在播放期間從媒體開頭移除的時間長度（毫秒）。寫入 **float**。 |
| virtual void [set_Volume](./set_volume/)([AudioVolumeMode](../audiovolumemode/)) | 設定音訊音量。寫入 [AudioVolumeMode](../audiovolumemode/)。 |
| virtual void [set_VolumeValue](./set_volumevalue/)(**float**) | 設定音訊音量（百分比）。寫入 **float**。 |
| virtual void [set_Width](../ishape/set_width/)(**float**) | 設定形狀的寬度（以點為單位）。寫入 **float**。 |
| virtual void [set_X](../ishape/set_x/)(**float**) | 設定形狀左上角的 x 座標（以點為單位）。寫入 **float**。 |
| virtual void [set_Y](../ishape/set_y/)(**float**) | 設定形狀左上角的 y 座標（以點為單位）。寫入 **float**。 |
| virtual void [SetGeometryPath](../igeometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) | 從 [IGeometryPath](../igeometrypath/) 物件更新形狀幾何。座標必須相對於形狀的左上角。將形狀的類型（[ShapeType](../shapetype/)）變更為 [ShapeType::Custom](../shapetype/)。 |
| virtual void [SetGeometryPaths](../igeometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) | 從 [IGeometryPath](../igeometrypath/) 陣列更新形狀幾何。座標必須相對於形狀的左上角。將形狀的類型（[ShapeType](../shapetype/)）變更為 [ShapeType::Custom](../shapetype/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 設定第 n 個模板參數為弱指標（而非共享指標）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並傳回共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 守護物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | 將 [Shape](../shape/) 內容儲存為 SVG 檔案。 |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | 將 [Shape](../shape/) 內容儲存為 SVG 檔案。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 參見

* 類別 [IPictureFrame](../ipictureframe/)
* 命名空間 [Aspose::Slides](../)
* 程式庫 [Aspose.Slides](../../)