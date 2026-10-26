---
title: IEffectFormat
second_title: Aspose.Slides for C++ API 參考
description: 表示形狀的效果屬性。
type: docs
weight: 2029
url: /zh-hant/aspose.slides/ieffectformat/
---
## IEffectFormat 類別


表示形狀的效果屬性。

```cpp
class IEffectFormat : public Aspose::Slides::IEffectParamSource
```

## 方法

| 方法 | 說明 |
| --- | --- |
| virtual void [DisableBlurEffect](./disableblureffect/)() | 停用模糊效果。 |
| virtual void [DisableFillOverlayEffect](./disablefilloverlayeffect/)() | 停用填充覆蓋效果。 |
| virtual void [DisableGlowEffect](./disablegloweffect/)() | 停用發光效果。 |
| virtual void [DisableInnerShadowEffect](./disableinnershadoweffect/)() | 停用內部陰影效果。 |
| virtual void [DisableOuterShadowEffect](./disableoutershadoweffect/)() | 停用外部陰影效果。 |
| virtual void [DisablePresetShadowEffect](./disablepresetshadoweffect/)() | 停用預設陰影效果。 |
| virtual void [DisableReflectionEffect](./disablereflectioneffect/)() | 停用反射效果。 |
| virtual void [DisableSoftEdgeEffect](./disablesoftedgeeffect/)() | 停用柔和邊緣效果。 |
| virtual void [EnableFillOverlayEffect](./enablefilloverlayeffect/)() | 啟用填充覆蓋效果。 |
| virtual void [EnableGlowEffect](./enablegloweffect/)() | 啟用發光效果。 |
| virtual void [EnableInnerShadowEffect](./enableinnershadoweffect/)() | 啟用內部陰影效果。 |
| virtual void [EnableOuterShadowEffect](./enableoutershadoweffect/)() | 啟用外部陰影效果。 |
| virtual void [EnablePresetShadowEffect](./enablepresetshadoweffect/)() | 啟用預設陰影效果。 |
| virtual void [EnableReflectionEffect](./enablereflectioneffect/)() | 啟用反射效果。 |
| virtual void [EnableSoftEdgeEffect](./enablesoftedgeeffect/)() | 啟用柔和邊緣效果。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值（包括 NaN）。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值（包括 NaN）。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IBlur](../../aspose.slides.effects/iblur/)\> [get_BlurEffect](./get_blureffect/)() | 模糊效果。閱讀 [Effects::IBlur](../../aspose.slides.effects/iblur/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/)\> [get_FillOverlayEffect](./get_filloverlayeffect/)() | 填充覆蓋效果。閱讀 [Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IGlow](../../aspose.slides.effects/iglow/)\> [get_GlowEffect](./get_gloweffect/)() | 發光效果。閱讀 [Effects::IGlow](../../aspose.slides.effects/iglow/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/)\> [get_InnerShadowEffect](./get_innershadoweffect/)() | 內部陰影。閱讀 [Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/)。 |
| virtual **bool** [get_IsNoEffects](./get_isnoeffects/)() | 如果所有效果皆已停用（與剛建立的預設 [EffectFormat](../effectformat/) 物件相同）則傳回 true。唯讀 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/)\> [get_OuterShadowEffect](./get_outershadoweffect/)() | 外部陰影。閱讀 [Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/)\> [get_PresetShadowEffect](./get_presetshadoweffect/)() | 預設陰影。閱讀 [Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IReflection](../../aspose.slides.effects/ireflection/)\> [get_ReflectionEffect](./get_reflectioneffect/)() | 反射。閱讀 [Effects::IReflection](../../aspose.slides.effects/ireflection/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/)\> [get_SoftEdgeEffect](./get_softedgeeffect/)() | 柔和邊緣。閱讀 [Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與此物件關聯的參考計數器資料結構。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormatEffectiveData](../ieffectformateffectivedata/)\> [GetEffective](./geteffective/)() | 取得套用繼承後的有效效果格式資料。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊功能。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為目標型別所描述的實例。相當於 C# 的 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監護物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用客製類型的克隆功能。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 賦值運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式將值型別物件與 nullptr 比較。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 針對字串與 nullptr 情況的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 針對字串情況的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
| virtual void [set_BlurEffect](./set_blureffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IBlur](../../aspose.slides.effects/iblur/)\>) | 模糊效果。寫入 [Effects::IBlur](../../aspose.slides.effects/iblur/)。 |
| virtual void [set_FillOverlayEffect](./set_filloverlayeffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/)\>) | 填充覆蓋效果。寫入 [Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/)。 |
| virtual void [set_GlowEffect](./set_gloweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IGlow](../../aspose.slides.effects/iglow/)\>) | 發光效果。寫入 [Effects::IGlow](../../aspose.slides.effects/iglow/)。 |
| virtual void [set_InnerShadowEffect](./set_innershadoweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/)\>) | 內部陰影。寫入 [Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/)。 |
| virtual void [set_OuterShadowEffect](./set_outershadoweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/)\>) | 外部陰影。寫入 [Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/)。 |
| virtual void [set_PresetShadowEffect](./set_presetshadoweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/)\>) | 預設陰影。寫入 [Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/)。 |
| virtual void [set_ReflectionEffect](./set_reflectioneffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IReflection](../../aspose.slides.effects/ireflection/)\>) | 反射。寫入 [Effects::IReflection](../../aspose.slides.effects/ireflection/)。 |
| virtual void [set_SoftEdgeEffect](./set_softedgeeffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/)\>) | 柔和邊緣。寫入 [Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/)。 |
| virtual void [SetBlurEffect](./setblureffect/)(**double**, **bool**) | 設定模糊效果。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並傳回共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構式。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監護物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另請參閱

* 類別 [IEffectParamSource](../ieffectparamsource/)
* 名稱空間 [Aspose::Slides](../)
* 函式庫 [Aspose.Slides](../../)