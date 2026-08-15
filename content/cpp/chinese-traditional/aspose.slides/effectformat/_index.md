---
title: EffectFormat
second_title: Aspose.Slides for C++ API 參考
description: 表示形狀的效果屬性。
type: docs
weight: 846
url: /zh-hant/aspose.slides/effectformat/
---
## EffectFormat 類別

表示形狀的效果屬性。

```cpp
class EffectFormat : public Aspose::Slides::PVIObject,
                     public Aspose::Slides::IEffectFormat
```

## 方法

| 方法 | 描述 |
| --- | --- |
| void [DisableBlurEffect](./disableblureffect/)() override | 停用模糊效果。 |
| void [DisableFillOverlayEffect](./disablefilloverlayeffect/)() override | 停用填充覆蓋效果。 |
| void [DisableGlowEffect](./disablegloweffect/)() override | 停用發光效果。 |
| void [DisableInnerShadowEffect](./disableinnershadoweffect/)() override | 停用內部陰影效果。 |
| void [DisableOuterShadowEffect](./disableoutershadoweffect/)() override | 停用外部陰影效果。 |
| void [DisablePresetShadowEffect](./disablepresetshadoweffect/)() override | 停用預設陰影效果。 |
| void [DisableReflectionEffect](./disablereflectioneffect/)() override | 停用反射效果。 |
| void [DisableSoftEdgeEffect](./disablesoftedgeeffect/)() override | 停用柔和邊緣效果。 |
| void [EnableFillOverlayEffect](./enablefilloverlayeffect/)() override | 啟用填充覆蓋效果。 |
| void [EnableGlowEffect](./enablegloweffect/)() override | 啟用發光效果。 |
| void [EnableInnerShadowEffect](./enableinnershadoweffect/)() override | 啟用內部陰影效果。 |
| void [EnableOuterShadowEffect](./enableoutershadoweffect/)() override | 啟用外部陰影效果。 |
| void [EnablePresetShadowEffect](./enablepresetshadoweffect/)() override | 啟用預設陰影效果。 |
| void [EnableReflectionEffect](./enablereflectioneffect/)() override | 啟用反射效果。 |
| void [EnableSoftEdgeEffect](./enablesoftedgeeffect/)() override | 啟用柔和邊緣效果。 |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 與指定的物件比較。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使依 IEC 60559:1989 標準，NaN 與任何值（包括 NaN）皆不相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使依 IEC 60559:1989 標準，NaN 與任何值（包括 NaN）皆不相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::IBlur](../../aspose.slides.effects/iblur/)\> [get_BlurEffect](./get_blureffect/)() override | 模糊效果。閱讀 [Effects::IBlur](../../aspose.slides.effects/iblur/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/)\> [get_FillOverlayEffect](./get_filloverlayeffect/)() override | 填充覆蓋效果。閱讀 [Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::IGlow](../../aspose.slides.effects/iglow/)\> [get_GlowEffect](./get_gloweffect/)() override | 發光效果。閱讀 [Effects::IGlow](../../aspose.slides.effects/iglow/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/)\> [get_InnerShadowEffect](./get_innershadoweffect/)() override | 內部陰影。閱讀 [Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/)。 |
| **bool** [get_IsNoEffects](./get_isnoeffects/)() override | 如果所有效果皆已停用（如剛建立的預設 [EffectFormat](./) 物件），則傳回 true。唯讀 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/)\> [get_OuterShadowEffect](./get_outershadoweffect/)() override | 外部陰影。閱讀 [Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/)。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | 傳回 Parent_Immediate 物件。唯讀 [IDOMObject](../idomobject/)。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | 傳回父層 [IPresentationComponent](../ipresentationcomponent/)。唯讀 [IPresentationComponent](../ipresentationcomponent/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/)\> [get_PresetShadowEffect](./get_presetshadoweffect/)() override | 預設陰影。閱讀 [Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::IReflection](../../aspose.slides.effects/ireflection/)\> [get_ReflectionEffect](./get_reflectioneffect/)() override | 反射。閱讀 [Effects::IReflection](../../aspose.slides.effects/ireflection/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/)\> [get_SoftEdgeEffect](./get_softedgeeffect/)() override | 柔和邊緣。閱讀 [Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件關聯的參考計數器資料結構。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormatEffectiveData](../ieffectformateffectivedata/)\> [GetEffective](./geteffective/)() override | 取得套用繼承後的有效效果格式資料。 |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | 傳回雜湊碼。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。相當於 C# 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂類型的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 賦值運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式將值型別物件與 nullptr 比較。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串與 nullptr 情況下的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串情況下的特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共用參考計數減少指定值。 |
| void [set_BlurEffect](./set_blureffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IBlur](../../aspose.slides.effects/iblur/)\>) override | 模糊效果。寫入 [Effects::IBlur](../../aspose.slides.effects/iblur/)。 |
| void [set_FillOverlayEffect](./set_filloverlayeffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/)\>) override | 填充覆蓋效果。寫入 [Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/)。 |
| void [set_GlowEffect](./set_gloweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IGlow](../../aspose.slides.effects/iglow/)\>) override | 發光效果。寫入 [Effects::IGlow](../../aspose.slides.effects/iglow/)。 |
| void [set_InnerShadowEffect](./set_innershadoweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/)\>) override | 內部陰影。寫入 [Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/)。 |
| void [set_OuterShadowEffect](./set_outershadoweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/)\>) override | 外部陰影。寫入 [Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/)。 |
| void [set_PresetShadowEffect](./set_presetshadoweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/)\>) override | 預設陰影。寫入 [Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/)。 |
| void [set_ReflectionEffect](./set_reflectioneffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IReflection](../../aspose.slides.effects/ireflection/)\>) override | 反射。寫入 [Effects::IReflection](../../aspose.slides.effects/ireflection/)。 |
| void [set_SoftEdgeEffect](./set_softedgeeffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/)\>) override | 柔和邊緣。寫入 [Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/)。 |
| void [SetBlurEffect](./setblureffect/)(**double**, **bool**) override | 設定模糊效果。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得目前的共用參考計數值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共用參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並傳回共用參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。允許將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 參見

* 類別 [PVIObject](../pviobject/)
* 類別 [IEffectFormat](../ieffectformat/)
* 命名空間 [Aspose::Slides](../)
* 函式庫 [Aspose.Slides](../../)