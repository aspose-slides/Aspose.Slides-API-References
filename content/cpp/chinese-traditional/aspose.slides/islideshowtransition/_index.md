---
title: ISlideShowTransition
second_title: Aspose.Slides for C++ API 參考
description: 表示投影片放映過渡效果。
type: docs
weight: 3810
url: /zh-hant/aspose.slides/islideshowtransition/
---
## ISlideShowTransition 類別

表示投影片放映過渡效果。

```cpp
class ISlideShowTransition : public virtual System::Object
```

## 方法

| 方法 | 說明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點數比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989 標準，NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點數比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989 標準，NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| virtual **bool** [get_AdvanceAfter](./get_advanceafter/)() | 此屬性指定投影片是否會在特定時間後移至下一張投影片。讀取 **bool**。 |
| virtual **uint32_t** [get_AdvanceAfterTime](./get_advanceaftertime/)() | 指定過渡應在多少毫秒後開始。此設定可與 advClick 屬性一起使用。如果未指定此屬性，則假設不會自動前進。讀取 **uint32_t**。 |
| virtual **bool** [get_AdvanceOnClick](./get_advanceonclick/)() | 指定滑鼠點擊是否會前進投影片。如果未指定此屬性，則預設值為 true。讀取 **bool**。 |
| virtual **int32_t** [get_Duration](./get_duration/)() | 取得投影片過渡效果的持續時間（以毫秒為單位）。讀取 **int32_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_Sound](./get_sound/)() | 返回嵌入的音訊資料。讀取 [IAudio](../iaudio/)。 |
| virtual **bool** [get_SoundIsBuiltIn](./get_soundisbuiltin/)() | 指定此音效是否為內建音效。如果此屬性設為 true，則會通知產生此音效的應用程式檢查在其內建音效清單中為此音效指定的 name 屬性，並可視需要顯示自訂名稱或介面。讀取 **bool**。 |
| virtual **bool** [get_SoundLoop](./get_soundloop/)() | 此屬性指定音效是否會持續循環，直至投影片中下一個音效事件發生。讀取 **bool**。 |
| virtual [SlideShow::TransitionSoundMode](../../aspose.slides.slideshow/transitionsoundmode/) [get_SoundMode](./get_soundmode/)() | 設定或返回投影片過渡的音效模式。讀取 [TransitionSoundMode](../../aspose.slides.slideshow/transitionsoundmode/)。 |
| virtual [System::String](../../system/string/) [get_SoundName](./get_soundname/)() | 指定過渡音效的人類可讀名稱。必須指派 [ISlideShowTransition::set_Sound](./set_sound/) 以取得或設定音效名稱。讀取 [System::String](../../system/string/)。 |
| virtual [SlideShow::TransitionSpeed](../../aspose.slides.slideshow/transitionspeed/) [get_Speed](./get_speed/)() | 指定從目前投影片過渡至下一張投影片時使用的過渡速度。讀取 [TransitionSpeed](../../aspose.slides.slideshow/transitionspeed/)。 |
| virtual [SlideShow::TransitionType](../../aspose.slides.slideshow/transitiontype/) [get_Type](./get_type/)() | 過渡類型。讀取 [TransitionType](../../aspose.slides.slideshow/transitiontype/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[SlideShow::ITransitionValueBase](../../aspose.slides.slideshow/itransitionvaluebase/)\> [get_Value](./get_value/)() | [Slide](../slide/) 顯示過渡值。唯讀 [SlideShow::ITransitionValueBase](../../aspose.slides.slideshow/itransitionvaluebase/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊功能。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。相當於 C# 的 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視器物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂類型的複製。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷貝建構函式。實際上不會複製任何內容，只是初始化新物件並允許子類別的拷貝建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的拷貝建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
| virtual void [set_AdvanceAfter](./set_advanceafter/)(**bool**) | 此屬性指定投影片是否會在特定時間後移至下一張投影片。寫入 **bool**。 |
| virtual void [set_AdvanceAfterTime](./set_advanceaftertime/)(**uint32_t**) | 指定過渡應在多少毫秒後開始。此設定可與 advClick 屬性一起使用。如果未指定此屬性，則假設不會自動前進。寫入 **uint32_t**。 |
| virtual void [set_AdvanceOnClick](./set_advanceonclick/)(**bool**) | 指定滑鼠點擊是否會前進投影片。如果未指定此屬性，則預設值為 true。寫入 **bool**。 |
| virtual void [set_Duration](./set_duration/)(**int32_t**) | 設定投影片過渡效果的持續時間（以毫秒為單位）。寫入 **int32_t**。 |
| virtual void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) | 設定嵌入的音訊資料。寫入 [IAudio](../iaudio/)。 |
| virtual void [set_SoundIsBuiltIn](./set_soundisbuiltin/)(**bool**) | 指定此音效是否為內建音效。如果此屬性設為 true，則會通知產生此音效的應用程式檢查在其內建音效清單中為此音效指定的 name 屬性，並可視需要顯示自訂名稱或介面。寫入 **bool**。 |
| virtual void [set_SoundLoop](./set_soundloop/)(**bool**) | 此屬性指定音效是否會持續循環，直至投影片中下一個音效事件發生。寫入 **bool**。 |
| virtual void [set_SoundMode](./set_soundmode/)([SlideShow::TransitionSoundMode](../../aspose.slides.slideshow/transitionsoundmode/)) | 設定或返回投影片過渡的音效模式。寫入 [TransitionSoundMode](../../aspose.slides.slideshow/transitionsoundmode/)。 |
| virtual void [set_SoundName](./set_soundname/)([System::String](../../system/string/)) | 指定過渡音效的人類可讀名稱。必須指派 [ISlideShowTransition::set_Sound](./set_sound/) 以取得或設定音效名稱。寫入 [System::String](../../system/string/)。 |
| virtual void [set_Speed](./set_speed/)([SlideShow::TransitionSpeed](../../aspose.slides.slideshow/transitionspeed/)) | 指定從目前投影片過渡至下一張投影片時使用的過渡速度。寫入 [TransitionSpeed](../../aspose.slides.slideshow/transitionspeed/)。 |
| virtual void [set_Type](./set_type/)([SlideShow::TransitionType](../../aspose.slides.slideshow/transitiontype/)) | 過渡類型。寫入 [TransitionType](../../aspose.slides.slideshow/transitiontype/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 設定第 n 個模板參數為弱指標（而非共享指標）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並返回共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視器物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另見

* 類別 [Object](../../system/object/)
* 命名空間 [Aspose::Slides](../)
* 函式庫 [Aspose.Slides](../../)