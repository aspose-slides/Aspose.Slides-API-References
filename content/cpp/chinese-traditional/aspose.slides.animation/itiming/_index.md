---
title: ITiming
second_title: Aspose.Slides for C++ API 參考
description: 表示動畫計時。
type: docs
weight: 443
url: /zh-hant/aspose.slides.animation/itiming/
---
## ITiming 類別

表示動畫計時。

```cpp
class ITiming : public virtual System::Object
```

## 方法

| 方法 | 說明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語義比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別的物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別的物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| virtual **float** [get_Accelerate](./get_accelerate/)() | 描述持續時間加速行為效果的百分比。讀取 **float**。 |
| virtual **bool** [get_AutoReverse](./get_autoreverse/)() | 描述是否在正向播放後自動逆向播放動畫。讀取 **bool**。 |
| virtual **float** [get_Decelerate](./get_decelerate/)() | 描述持續時間減速行為效果的百分比。讀取 **float**。 |
| virtual **float** [get_Duration](./get_duration/)() | 描述動畫效果的持續時間。讀取 **float**。 |
| virtual **float** [get_RepeatCount](./get_repeatcount/)() | 描述效果應重複的次數。讀取 **float**。 |
| virtual **float** [get_RepeatDuration](./get_repeatduration/)() | 描述效果應重複的次數。讀取 **float**。 |
| virtual **bool** [get_RepeatUntilEndSlide](./get_repeatuntilendslide/)() | 此屬性指定效果是否會持續重複至投影片結束。讀取 **bool**。 |
| virtual **bool** [get_RepeatUntilNextClick](./get_repeatuntilnextclick/)() | 此屬性指定效果是否會持續重複至下一次點擊。讀取 **bool**。 |
| virtual [EffectRestartType](../effectrestarttype/) [get_Restart](./get_restart/)() | 指定效果完成後是否重新啟動。讀取 [EffectRestartType](../effectrestarttype/)。 |
| virtual **bool** [get_Rewind](./get_rewind/)() | 此屬性指定效果在播放完畢後是否會倒轉。讀取 **bool**。 |
| virtual **float** [get_Speed](./get_speed/)() | 指定時間加速（或減速）的百分比。讀取 **float**。 |
| virtual **float** [get_TriggerDelayTime](./get_triggerdelaytime/)() | 描述觸發後的延遲時間。讀取 **float**。 |
| virtual [EffectTriggerType](../effecttriggertype/) [get_TriggerType](./get_triggertype/)() | 描述觸發類型。讀取 [EffectTriggerType](../effecttriggertype/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數器資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。允許對自訂物件進行雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述型別的實例。相當於 C# 的 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 哨兵物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。允許複製自訂型別。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不會複製任何內容，只是初始化新的物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 賦值運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 針對字串與 nullptr 情況的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 針對字串情況的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
| virtual void [set_Accelerate](./set_accelerate/)(**float**) | 描述持續時間加速行為效果的百分比。寫入 **float**。 |
| virtual void [set_AutoReverse](./set_autoreverse/)(**bool**) | 描述是否在正向播放後自動逆向播放動畫。寫入 **bool**。 |
| virtual void [set_Decelerate](./set_decelerate/)(**float**) | 描述持續時間減速行為效果的百分比。寫入 **float**。 |
| virtual void [set_Duration](./set_duration/)(**float**) | 描述動畫效果的持續時間。寫入 **float**。 |
| virtual void [set_RepeatCount](./set_repeatcount/)(**float**) | 描述效果應重複的次數。寫入 **float**。 |
| virtual void [set_RepeatDuration](./set_repeatduration/)(**float**) | 描述效果應重複的次數。寫入 **float**。 |
| virtual void [set_RepeatUntilEndSlide](./set_repeatuntilendslide/)(**bool**) | 此屬性指定效果是否會持續重複至投影片結束。寫入 **bool**。 |
| virtual void [set_RepeatUntilNextClick](./set_repeatuntilnextclick/)(**bool**) | 此屬性指定效果是否會持續重複至下一次點擊。寫入 **bool**。 |
| virtual void [set_Restart](./set_restart/)([EffectRestartType](../effectrestarttype/)) | 指定效果完成後是否重新啟動。寫入 [EffectRestartType](../effectrestarttype/)。 |
| virtual void [set_Rewind](./set_rewind/)(**bool**) | 此屬性指定效果在播放完畢後是否會倒轉。寫入 **bool**。 |
| virtual void [set_Speed](./set_speed/)(**float**) | 指定時間加速（或減速）的百分比。寫入 **float**。 |
| virtual void [set_TriggerDelayTime](./set_triggerdelaytime/)(**float**) | 描述觸發後的延遲時間。寫入 **float**。 |
| virtual void [set_TriggerType](./set_triggertype/)([EffectTriggerType](../effecttriggertype/)) | 描述觸發類型。寫入 [EffectTriggerType](../effecttriggertype/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設定為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數器的當前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。允許將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 哨兵物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 參見

* 類別 [Object](../../system/object/)
* 命名空間 [Aspose::Slides::Animation](../)
* 函式庫 [Aspose.Slides](../../)