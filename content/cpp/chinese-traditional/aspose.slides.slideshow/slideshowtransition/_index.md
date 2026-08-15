---
title: SlideShowTransition
second_title: Aspose.Slides for C++ API 參考
description: 表示投影片放映過渡。
type: docs
weight: 404
url: /zh-hant/aspose.slides.slideshow/slideshowtransition/
---
## SlideShowTransition 類別

表示投影片放映過渡。

```cpp
class SlideShowTransition : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::BaseSlide>>,
                            public Aspose::Slides::ISlideShowTransition
```

## 方法

| 方法 | 描述 |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 判斷兩個 [SlideShowTransition](./) 實例是否相等。讀寫 **bool**。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別的物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，在此比較中即使根據 IEC 60559:1989，NaN 不等於任何值（包括 NaN），兩個 NaN 仍被視為相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，在此比較中即使根據 IEC 60559:1989，NaN 不等於任何值（包括 NaN），兩個 NaN 仍被視為相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| **bool** [get_AdvanceAfter](./get_advanceafter/)() override | 此屬性指定投影片是否在一定時間後移動到下一張投影片。讀 **bool**。 |
| **uint32_t** [get_AdvanceAfterTime](./get_advanceaftertime/)() override | 指定過渡應開始的時間（以毫秒為單位）。此設定可與 advClick 屬性一起使用。如果未指定此屬性，則預設不會自動前進。讀 **uint32_t**。 |
| **bool** [get_AdvanceOnClick](./get_advanceonclick/)() override | 指定滑鼠點擊是否會前進投影片。如果未指定此屬性，則預設為 true。讀 **bool**。 |
| **int32_t** [get_Duration](./get_duration/)() override | 取得投影片過渡效果的持續時間（以毫秒為單位）。讀 **int32_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\> [get_Sound](./get_sound/)() override | 傳回嵌入的音訊資料。讀 [IAudio](../../aspose.slides/iaudio/)。 |
| **bool** [get_SoundIsBuiltIn](./get_soundisbuiltin/)() override | 指定此音效是否為內建音效。如果此屬性設為 true，則會提示產生此檔案的應用程式檢查此音效在內建音效清單中指定的 name 屬性，並可依需求顯示自訂名稱或 UI。讀 **bool**。 |
| **bool** [get_SoundLoop](./get_soundloop/)() override | 此屬性指定音效是否會持續循環，直至投影片中下一個音效事件發生。讀 **bool**。 |
| [TransitionSoundMode](../transitionsoundmode/) [get_SoundMode](./get_soundmode/)() override | 設定或傳回投影片過渡的音效模式。讀 [TransitionSoundMode](../transitionsoundmode/)。 |
| [System::String](../../system/string/) [get_SoundName](./get_soundname/)() override | 指定過渡音效的可讀名稱。必須分配 [ISlideShowTransition::set_Sound](../../aspose.slides/islideshowtransition/set_sound/) 以取得或設定音效名稱。讀 [System::String](../../system/string/)。 |
| [TransitionSpeed](../transitionspeed/) [get_Speed](./get_speed/)() override | 指定從目前投影片過渡到下一張時使用的過渡速度。讀 [TransitionSpeed](../transitionspeed/)。 |
| [TransitionType](../transitiontype/) [get_Type](./get_type/)() override | 過渡類型。讀 [TransitionType](../transitiontype/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ITransitionValueBase](../itransitionvaluebase/)\> [get_Value](./get_value/)() override | [Slide](../../aspose.slides/slide/) 顯示過渡值。唯讀 [ITransitionValueBase](../itransitionvaluebase/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數器資料結構。 |
| **int32_t** [GetHashCode](./gethashcode/)() const override | 作為特定型別的雜湊函式，可用於雜湊演算法及像雜湊表之類的資料結構。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述型別的實例。相當於 C# 的 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。可直接呼叫或使用 [LockContext](../../system/lockcontext/) 哨兵物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂型別的複製。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構函式。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式將值型別物件與 nullptr 比較。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串與 nullptr 情況下的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串情況下的特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 依指定值減少共享參考計數。 |
| void [set_AdvanceAfter](./set_advanceafter/)(**bool**) override | 此屬性指定投影片是否在一定時間後移動到下一張投影片。寫 **bool**。 |
| void [set_AdvanceAfterTime](./set_advanceaftertime/)(**uint32_t**) override | 指定過渡應開始的時間（以毫秒為單位）。此設定可與 advClick 屬性一起使用。如果未指定此屬性，則預設不會自動前進。寫 **uint32_t**。 |
| void [set_AdvanceOnClick](./set_advanceonclick/)(**bool**) override | 指定滑鼠點擊是否會前進投影片。如果未指定此屬性，則預設為 true。寫 **bool**。 |
| void [set_Duration](./set_duration/)(**int32_t**) override | 設定投影片過渡效果的持續時間（以毫秒為單位）。寫 **int32_t**。 |
| void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\>) override | 設定嵌入的音訊資料。寫 [IAudio](../../aspose.slides/iaudio/)。 |
| void [set_SoundIsBuiltIn](./set_soundisbuiltin/)(**bool**) override | 指定此音效是否為內建音效。如果此屬性設定為 true，則會提示產生此檔案的應用程式檢查此音效在內建音效清單中指定的 name 屬性，並可依需求顯示自訂名稱或 UI。寫 **bool**。 |
| void [set_SoundLoop](./set_soundloop/)(**bool**) override | 此屬性指定音效是否會持續循環，直至投影片中下一個音效事件發生。寫 **bool**。 |
| void [set_SoundMode](./set_soundmode/)([TransitionSoundMode](../transitionsoundmode/)) override | 設定或傳回投影片過渡的音效模式。寫 [TransitionSoundMode](../transitionsoundmode/)。 |
| void [set_SoundName](./set_soundname/)([System::String](../../system/string/)) override | 指定過渡音效的可讀名稱。必須分配 [ISlideShowTransition::set_Sound](../../aspose.slides/islideshowtransition/set_sound/) 以取得或設定音效名稱。寫 [System::String](../../system/string/)。 |
| void [set_Speed](./set_speed/)([TransitionSpeed](../transitionspeed/)) override | 指定從目前投影片過渡到下一張時使用的過渡速度。寫 [TransitionSpeed](../transitionspeed/)。 |
| void [set_Type](./set_type/)([TransitionType](../transitiontype/)) override | 過渡類型。寫 [TransitionType](../transitiontype/)。 |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | 設定第 n 個模板參數為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數器的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並傳回共享參考計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。可直接呼叫或使用 [LockContext](../../system/lockcontext/) 哨兵物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 參見

* 類別 [DomObject](../../aspose.slides/domobject/)
* 類別 [ISlideShowTransition](../../aspose.slides/islideshowtransition/)
* 命名空間 [Aspose::Slides::SlideShow](../)
* 函式庫 [Aspose.Slides](../../)