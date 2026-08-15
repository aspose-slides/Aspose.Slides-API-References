---
title: IOverrideTheme
second_title: Aspose.Slides for C++ API 參考
description: 表示一個覆寫佈景主題。
type: docs
weight: 391
url: /zh-hant/aspose.slides.theme/ioverridetheme/
---
## IOverrideTheme 類別

表示一個覆寫佈景主題。

```cpp
class IOverrideTheme : public virtual Aspose::Slides::Theme::ITheme
```

## 方法

| 方法 | 說明 |
| --- | --- |
| virtual void [Clear](./clear/)() | 將 [ColorScheme](../colorscheme/)、[FontScheme](../fontscheme/)、[FormatScheme](../formatscheme/) 設為 null 以停用此佈景主題物件的任何覆寫。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使依據 IEC 60559:1989 NaN 與任何值（包括 NaN）皆不相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使依據 IEC 60559:1989 NaN 與任何值（包括 NaN）皆不相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_ColorFormat](../itheme/get_colorformat/)([ColorSchemeIndex](../../aspose.slides/colorschemeindex/)) |  |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorScheme](../icolorscheme/)\> [get_ColorScheme](../itheme/get_colorscheme/)() | 返回顏色配置方案。唯讀 [IColorScheme](../icolorscheme/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontScheme](../ifontscheme/)\> [get_FontScheme](../itheme/get_fontscheme/)() | 返回字型配置方案。唯讀 [IFontScheme](../ifontscheme/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormatScheme](../iformatscheme/)\> [get_FormatScheme](../itheme/get_formatscheme/)() | 返回圖形格式配置方案。唯讀 [IFormatScheme](../iformatscheme/)。 |
| virtual **bool** [get_IsEmpty](./get_isempty/)() | True 值表示 [ColorScheme](../colorscheme/)、[FontScheme](../fontscheme/)、[FormatScheme](../formatscheme/) 為 null，且此佈景主題物件的任何覆寫均已停用。唯讀 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | 返回簡報。唯讀 [IPresentation](../../aspose.slides/ipresentation/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數器資料結構。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThemeEffectiveData](../ithemeeffectivedata/)\> [GetEffective](../itheme/geteffective/)() | 取得套用繼承後的有效佈景資料。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual void [InitColorScheme](./initcolorscheme/)() | 使用新物件初始化 [ColorScheme](../colorscheme/) 以覆寫 InheritedTheme 的 [ColorScheme](../colorscheme/)。 |
| virtual void [InitColorSchemeFrom](./initcolorschemefrom/)([System::SharedPtr](../../system/sharedptr/)\<[IColorScheme](../icolorscheme/)\>) | 使用新物件初始化 [ColorScheme](../colorscheme/) 以覆寫 InheritedTheme 的 [ColorScheme](../colorscheme/)。 |
| virtual void [InitColorSchemeFromInherited](./initcolorschemefrominherited/)() | 使用新物件初始化 [ColorScheme](../colorscheme/) 以覆寫 InheritedTheme 的 [ColorScheme](../colorscheme/)。並以 InheritedTheme 的 [ColorScheme](../colorscheme/) 資料初始化此新物件的資料。 |
| virtual void [InitFontScheme](./initfontscheme/)() | 使用新物件初始化 [FontScheme](../fontscheme/) 以覆寫 InheritedTheme 的 [FontScheme](../fontscheme/)。 |
| virtual void [InitFontSchemeFrom](./initfontschemefrom/)([System::SharedPtr](../../system/sharedptr/)\<[IFontScheme](../ifontscheme/)\>) | 使用新物件初始化 [FontScheme](../fontscheme/) 以覆寫 InheritedTheme 的 [FontScheme](../fontscheme/)。 |
| virtual void [InitFontSchemeFromInherited](./initfontschemefrominherited/)() | 使用新物件初始化 [FontScheme](../fontscheme/) 以覆寫 InheritedTheme 的 [FontScheme](../fontscheme/)。並以 InheritedTheme 的 [FontScheme](../fontscheme/) 資料初始化此新物件的資料。 |
| virtual void [InitFormatScheme](./initformatscheme/)() | 使用新物件初始化 [FormatScheme](../formatscheme/) 以覆寫 InheritedTheme 的 [FormatScheme](../formatscheme/)。 |
| virtual void [InitFormatSchemeFrom](./initformatschemefrom/)([System::SharedPtr](../../system/sharedptr/)\<[IFormatScheme](../iformatscheme/)\>) | 使用新物件初始化 [FormatScheme](../formatscheme/) 以覆寫 InheritedTheme 的 [FormatScheme](../formatscheme/)。 |
| virtual void [InitFormatSchemeFromInherited](./initformatschemefrominherited/)() | 使用新物件初始化 [FormatScheme](../formatscheme/) 以覆寫 InheritedTheme 的 [FormatScheme](../formatscheme/)。並以 InheritedTheme 的 [FormatScheme](../formatscheme/) 資料初始化此新物件的資料。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述型別的實例。相當於 C# 的 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂型別的複製。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 副本建構式。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式將值型別物件與 nullptr 比較。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設定為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數器的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並返回共享參考計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另請參閱

* 類別 [ITheme](../itheme/)
* 命名空間 [Aspose::Slides::Theme](../)
* 函式庫 [Aspose.Slides](../../)