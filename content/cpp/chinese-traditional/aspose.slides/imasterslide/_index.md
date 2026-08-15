---
title: IMasterSlide
second_title: Aspose.Slides for C++ API 參考
description: 代表簡報中的母版投影片。
type: docs
weight: 2926
url: /zh-hant/aspose.slides/imasterslide/
---
## IMasterSlide 類別


Represents a master slide in a presentation.

```cpp
class IMasterSlide : public virtual Aspose::Slides::IBaseSlide,
                     public Aspose::Slides::Theme::IMasterThemeable
```

## 方法

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMasterSlide](./)\> [ApplyExternalThemeToDependingSlides](./applyexternalthemetodependingslides/)([System::String](../../system/string/)) | 根據目前的母片建立新的母片，套用外部主題，並將建立的母片套用至所有相依投影片。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](../../aspose.slides.theme/ithemeable/createthemeeffective/)() | 傳回此可套用主題之物件的實際主題。 |
| virtual **bool** [Equals](../ibaseslide/equals/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\>) | 判斷兩個 [IBaseSlide](../ibaseslide/) 實例是否相等。返回值根據投影片的結構與靜態內容計算。若所有形狀、樣式、文字、動畫及其他設定等皆相同，則兩張投影片相等。比較不會考慮唯一識別碼值，例如 SlideId，以及動態內容，例如日期 [Placeholder](../placeholder/) 中的目前日期值。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使依 IEC 60559:1989 規範 NaN 與任何值（包括 NaN）皆不相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使依 IEC 60559:1989 規範 NaN 與任何值（包括 NaN）皆不相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [FindShapeByAltText](../ibaseslide/findshapebyalttext/)([System::String](../../system/string/)) | 尋找具指定替代文字的圖形之首次出現。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBackground](../ibackground/)\> [get_Background](../ibaseslide/get_background/)() | 傳回投影片的背景。唯讀 [IBackground](../ibackground/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_BodyStyle](./get_bodystyle/)() | 傳回正文文字的樣式。唯讀 [ITextStyle](../itextstyle/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IControl](../icontrol/)\> [get_Control](../ibaseslide/get_control/)(**int32_t**) | 傳回指定索引處的 ActiveX 控制項。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IControlCollection](../icontrolcollection/)\> [get_Controls](../ibaseslide/get_controls/)() | 傳回投影片上所有 ActiveX 控制項的集合。唯讀 [IControlCollection](../icontrolcollection/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ibaseslide/get_customdata/)() | 傳回投影片的自訂資料。唯讀 [ICustomData](../icustomdata/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDrawingGuidesCollection](../idrawingguidescollection/)\> [get_DrawingGuides](./get_drawingguides/)() | 傳回母片的繪圖參考線集合。唯讀 [IDrawingGuidesCollection](../idrawingguidescollection/) |
| virtual **bool** [get_HasDependingSlides](./get_hasdependingslides/)() | 若至少有一張投影片相依此母片，則傳回 true。唯讀 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMasterSlideHeaderFooterManager](../imasterslideheaderfootermanager/)\> [get_HeaderFooterManager](./get_headerfootermanager/)() | 傳回母片的 HeaderFooter 管理器。唯讀 [IMasterSlideHeaderFooterManager](../imasterslideheaderfootermanager/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkQueries](../ihyperlinkqueries/)\> [get_HyperlinkQueries](../ibaseslide/get_hyperlinkqueries/)() | 提供對所包含超連結的簡易存取。唯讀 [IHyperlinkQueries](../ihyperlinkqueries/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\> [get_LayoutSlide](./get_layoutslide/)(**int32_t**) | 傳回此母片在指定索引處的子版面投影片。唯讀 [Aspose::Slides::ILayoutSlide](../ilayoutslide/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMasterLayoutSlideCollection](../imasterlayoutslidecollection/)\> [get_LayoutSlides](./get_layoutslides/)() | 傳回此母片的子版面投影片集合。唯讀 [IMasterLayoutSlideCollection](../imasterlayoutslidecollection/)。 |
| virtual [System::String](../../system/string/) [get_Name](../ibaseslide/get_name/)() | 傳回投影片的名稱。讀取 [System::String](../../system/string/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_OtherStyle](./get_otherstyle/)() | 傳回其他文字的樣式。唯讀 [ITextStyle](../itextstyle/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | 傳回簡報。唯讀 [IPresentation](../ipresentation/)。 |
| virtual **bool** [get_Preserve](./get_preserve/)() | 判斷當所有跟隨該母片的投影片皆被刪除時，對應的母片是否亦被刪除。注意：[Aspose.Slides](../) 不會自行移除任何未使用的母片，若需實際移除未使用的母片，請呼叫 [IMasterSlideCollection::RemoveUnused](../imasterslidecollection/removeunused/)。讀取 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_Shape](../ibaseslide/get_shape/)(**int32_t**) | 傳回指定索引處的圖形。唯讀 [Aspose::Slides::IShape](../ishape/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\> [get_Shapes](../ibaseslide/get_shapes/)() | 傳回投影片的圖形。唯讀 [IShapeCollection](../ishapecollection/)。 |
| virtual **bool** [get_ShowMasterShapes](../ibaseslide/get_showmastershapes/)() | 指定母片上的圖形是否應在投影片上顯示。對於母片本身，此屬性永遠傳回 **false**。讀取 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | 傳回基礎投影片。唯讀 [IBaseSlide](../ibaseslide/)。 |
| virtual **uint32_t** [get_SlideId](../ibaseslide/get_slideid/)() | 傳回投影片的 ID。唯讀 **uint32_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlideShowTransition](../islideshowtransition/)\> [get_SlideShowTransition](../ibaseslide/get_slideshowtransition/)() | 傳回 TransitionEx 物件，該物件包含指定投影片於投影片放映時的前進資訊。唯讀 [ISlideShowTransition](../islideshowtransition/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMasterThemeManager](../../aspose.slides.theme/imasterthememanager/)\> [get_ThemeManager](../../aspose.slides.theme/imasterthemeable/get_thememanager/)() | 傳回母版主題管理器。唯讀 [IMasterThemeManager](../../aspose.slides.theme/imasterthememanager/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAnimationTimeLine](../ianimationtimeline/)\> [get_Timeline](../ibaseslide/get_timeline/)() | 傳回動畫時間軸物件。唯讀 [IAnimationTimeLine](../ianimationtimeline/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_TitleStyle](./get_titlestyle/)() | 傳回標題文字的樣式。唯讀 [ITextStyle](../itextstyle/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件關聯的參考計數資料結構。 |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [GetDependingSlides](./getdependingslides/)() | 傳回一個包含所有相依此母片的投影片之陣列。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。支援自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為由 targetType 描述的型別之實例。相當於 C# 的 'is' 運算子。 |
| virtual void [JoinPortionsWithSameFormatting](../ibaseslide/joinportionswithsameformatting/)() | 在所有可接受的圖形內的所有段落中，將格式相同的字元串合併。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監護物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。支援自訂型別的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構函式。實際上不會複製任何內容，只是初始化新物件並允許子類別進行複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 賦值運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別進行複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特殊化，適用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特殊化，適用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共用參考計數減少指定值。 |
| virtual void [set_Name](../ibaseslide/set_name/)([System::String](../../system/string/)) | 設定投影片的名稱。寫入 [System::String](../../system/string/)。 |
| virtual void [set_Preserve](./set_preserve/)(**bool**) | 判斷當所有跟隨該母片的投影片皆被刪除時，對應的母片是否亦被刪除。注意：[Aspose.Slides](../) 不會自行移除任何未使用的母片，若需實際移除未使用的母片，請呼叫 [IMasterSlideCollection::RemoveUnused](../imasterslidecollection/removeunused/)。寫入 **bool**。 |
| virtual void [set_ShowMasterShapes](../ibaseslide/set_showmastershapes/)(**bool**) | 指定母片上的圖形是否應在投影片上顯示。對於母片本身，此屬性永遠傳回 **false**。寫入 **bool**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設定為弱指標（而非共享指標）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共用參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共用參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並返回共用參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。支援將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構式。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監護物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另請參閱

* 類別 [IBaseSlide](../ibaseslide/)
* 類別 [IMasterThemeable](../../aspose.slides.theme/imasterthemeable/)
* 命名空間 [Aspose::Slides](../)
* 函式庫 [Aspose.Slides](../../)