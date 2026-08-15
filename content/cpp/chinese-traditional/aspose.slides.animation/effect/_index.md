---
title: Effect
second_title: Aspose.Slides for C++ API 參考文件
description: 表示動畫效果。
type: docs
weight: 118
url: /zh-hant/aspose.slides.animation/effect/
---
## Effect 類別

表示動畫效果。

```cpp
class Effect : public Aspose::Slides::Animation::IEffect,
               public Aspose::Slides::IDOMObject
```

## 方法

| 方法 | 說明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語義比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_AfterAnimationColor](./get_afteranimationcolor/)() override | 定義效果的後置動畫顏色。閱讀 [IColorFormat](../../aspose.slides/icolorformat/)。 |
| [Aspose::Slides::Animation::AfterAnimationType](../afteranimationtype/) [get_AfterAnimationType](./get_afteranimationtype/)() override | 定義效果的後置動畫類型。閱讀 [AfterAnimationType](../afteranimationtype/)。 |
| [Aspose::Slides::Animation::AnimateTextType](../animatetexttype/) [get_AnimateTextType](./get_animatetexttype/)() override | 定義動畫文字類型。形狀文字可以按字母、按單詞或一次全部動畫。閱讀 [AnimateTextType](../animatetexttype/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IBehavior](../ibehavior/)\> [get_Behavior](./get_behavior/)(**int32_t**) override | 返回指定索引處的動畫行為。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorCollection](../ibehaviorcollection/)\> [get_Behaviors](./get_behaviors/)() override | 返回效果的行為集合。閱讀 [IBehaviorCollection](../ibehaviorcollection/)。 |
| **float** [get_DelayBetweenTextParts](./get_delaybetweentextparts/)() override | 定義動畫文字部件（單詞或字母）之間的延遲。正值指定效果持續時間的百分比。負值指定以秒為單位的延遲。閱讀 **float**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffect](../ieffect/)\> [get_Effect](./get_effect/)(**int32_t**) override | 返回指定索引處序列的影響。 |
| [EffectPresetClassType](../effectpresetclasstype/) [get_PresetClassType](./get_presetclasstype/)() override | 定義效果的類別。閱讀 [EffectPresetClassType](../effectpresetclasstype/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISequence](../isequence/)\> [get_Sequence](./get_sequence/)() override | 返回效果的序列。唯讀 [ISequence](../isequence/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\> [get_Sound](./get_sound/)() override | 定義效果的嵌入式聲音。閱讀 [IAudio](../../aspose.slides/iaudio/)。 |
| **bool** [get_StopPreviousSound](./get_stopprevioussound/)() override | 此屬性指定動畫效果是否停止先前的聲音。閱讀 **bool**。 |
| [EffectSubtype](../effectsubtype/) [get_Subtype](./get_subtype/)() override | 定義效果的子類型。閱讀 [EffectSubtype](../effectsubtype/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [get_TargetShape](./get_targetshape/)() override | 返回效果的目標形狀。唯讀 [IShape](../../aspose.slides/ishape/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextAnimation](../itextanimation/)\> [get_TextAnimation](./get_textanimation/)() override | [TextAnimation](../textanimation/) 唯讀 [ITextAnimation](../itextanimation/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\> [get_Timing](./get_timing/)() override | 定義效果的時間值。閱讀 [ITiming](../itiming/)。 |
| [EffectType](../effecttype/) [get_Type](./get_type/)() override | 定義效果的類型。閱讀 [EffectType](../effecttype/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件關聯的引用計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法的類比。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。C# [System.Object.GetType()](../../system/object/gettype/) 呼叫的類比。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。C# 'is' 運算子的類比。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 哨兵物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法的類比。啟用自訂類型的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構函式。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製構造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 賦值運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製構造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 依參考比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 依參考比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考比較值型物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串和 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享引用計數減少指定值。 |
| void [set_AfterAnimationColor](./set_afteranimationcolor/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\>) override | 定義效果的後置動畫顏色。寫入 [IColorFormat](../../aspose.slides/icolorformat/)。 |
| void [set_AfterAnimationType](./set_afteranimationtype/)([Aspose::Slides::Animation::AfterAnimationType](../afteranimationtype/)) override | 定義效果的後置動畫類型。寫入 [AfterAnimationType](../afteranimationtype/)。 |
| void [set_AnimateTextType](./set_animatetexttype/)([Aspose::Slides::Animation::AnimateTextType](../animatetexttype/)) override | 定義動畫文字類型。形狀文字可以按字母、按單詞或一次全部動畫。寫入 [AnimateTextType](../animatetexttype/)。 |
| void [set_Behavior](./set_behavior/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IBehavior](../ibehavior/)\>) override | 設定指定索引處的動畫行為。 |
| void [set_Behaviors](./set_behaviors/)([System::SharedPtr](../../system/sharedptr/)\<[IBehaviorCollection](../ibehaviorcollection/)\>) override | 返回效果的行為集合。寫入 [IBehaviorCollection](../ibehaviorcollection/)。 |
| void [set_DelayBetweenTextParts](./set_delaybetweentextparts/)(**float**) override | 定義動畫文字部件（單詞或字母）之間的延遲。正值指定效果持續時間的百分比。負值指定以秒為單位的延遲。寫入 **float**。 |
| void [set_PresetClassType](./set_presetclasstype/)([EffectPresetClassType](../effectpresetclasstype/)) override | 定義效果的類別。寫入 [EffectPresetClassType](../effectpresetclasstype/)。 |
| void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\>) override | 定義效果的嵌入式聲音。寫入 [IAudio](../../aspose.slides/iaudio/)。 |
| void [set_StopPreviousSound](./set_stopprevioussound/)(**bool**) override | 此屬性指定動畫效果是否停止先前的聲音。寫入 **bool**。 |
| void [set_Subtype](./set_subtype/)([EffectSubtype](../effectsubtype/)) override | 定義效果的子類型。寫入 [EffectSubtype](../effectsubtype/)。 |
| void [set_Timing](./set_timing/)([System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\>) override | 定義效果的時間值。寫入 [ITiming](../itiming/)。 |
| void [set_Type](./set_type/)([EffectType](../effecttype/)) override | 定義效果的類型。寫入 [EffectType](../effecttype/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 設定第 n 個模板參數為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享引用計數的當前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享引用計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並返回共享引用計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 方法的類比。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 哨兵物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱引用計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱引用計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另見

* 類別 [IEffect](../ieffect/)
* 類別 [IDOMObject](../../aspose.slides/idomobject/)
* 命名空間 [Aspose::Slides::Animation](../)
* 函式庫 [Aspose.Slides](../../)