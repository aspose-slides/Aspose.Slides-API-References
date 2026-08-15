---
title: ParagraphFormat
second_title: Aspose.Slides for C++ API 參考
description: 此類別包含段落格式屬性。與 IParagraphFormatEffectiveData 不同，此類別的所有屬性皆可寫入。
type: docs
weight: 4668
url: /zh-hant/aspose.slides/paragraphformat/
---
## ParagraphFormat 類別


This class contains the paragraph formatting properties. Unlike [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/), all properties of this class are writeable.

```cpp
class ParagraphFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::IParagraphFormat,
                        public Aspose::Slides::Charts::IChartParagraphFormat
```

## 方法

| 方法 | 描述 |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 與指定的物件比較。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989，NaN 與任何值（包括 NaN）皆不相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989，NaN 與任何值（包括 NaN）皆不相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| [TextAlignment](../textalignment/) [get_Alignment](./get_alignment/)() override | 返回段落中未套用繼承的文字對齊方式。請參閱 [TextAlignment](../textalignment/)。 |
| **float** [get_DefaultTabSize](./get_defaulttabsize/)() override | 返回未套用繼承的預設定位大小。請參閱 **float**。 |
| [NullableBool](../nullablebool/) [get_EastAsianLineBreak](./get_eastasianlinebreak/)() override | 判斷段落是否使用東亞換行。未套用繼承。請參閱 [NullableBool](../nullablebool/)。 |
| [Aspose::Slides::FontAlignment](../fontalignment/) [get_FontAlignment](./get_fontalignment/)() override | 返回段落中未套用繼承的字體對齊方式。請參閱 [Slides::FontAlignment](../fontalignment/)。 |
| [NullableBool](../nullablebool/) [get_HangingPunctuation](./get_hangingpunctuation/)() override | 判斷段落是否使用懸掛標點。未套用繼承。請參閱 [NullableBool](../nullablebool/)。 |
| **float** [get_Indent](./get_indent/)() override | 返回段落未套用繼承的首行縮排/懸掛縮排。懸掛縮排可使用負值定義。請參閱 **float**。 |
| [NullableBool](../nullablebool/) [get_LatinLineBreak](./get_latinlinebreak/)() override | 判斷段落是否使用拉丁換行。未套用繼承。請參閱 [NullableBool](../nullablebool/)。 |
| **float** [get_MarginLeft](./get_marginleft/)() override | 返回段落未套用繼承的左邊距。請參閱 **float**。 |
| **float** [get_MarginRight](./get_marginright/)() override | 返回段落未套用繼承的右邊距。請參閱 **float**。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | 返回 Parent_Immediate 物件。唯讀 [IDOMObject](../idomobject/)。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | 返回父層 [IPresentationComponent](../ipresentationcomponent/)。唯讀 [IPresentationComponent](../ipresentationcomponent/)。 |
| [NullableBool](../nullablebool/) [get_RightToLeft](./get_righttoleft/)() override | 判斷段落是否使用從右至左書寫。未套用繼承。請參閱 [NullableBool](../nullablebool/)。 |
| **float** [get_SpaceAfter](./get_spaceafter/)() override | 返回段落未套用繼承的最後一行之後的空白量。正值指定空白的字型大小百分比，負值則以點數指定空白大小。請參閱 **float**。 |
| **float** [get_SpaceBefore](./get_spacebefore/)() override | 返回段落未套用繼承的第一行之前的空白量。正值指定空白的字型大小百分比，負值則以點數指定空白大小。請參閱 **float**。 |
| **float** [get_SpaceWithin](./get_spacewithin/)() override | 返回段落基線之間的空白量。正值表示百分比，負值表示點數大小。未套用繼承。請參閱 **float**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ITab](../itab/)\> [get_Tab](./get_tab/)(**int32_t**) override | 返回指定索引處段落的定位。未套用繼承。唯讀 [Aspose::Slides::ITab](../itab/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ITabCollection](../itabcollection/)\> [get_Tabs](./get_tabs/)() override | 返回段落的定位集合。未套用繼承。唯讀 [ITabCollection](../itabcollection/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormatEffectiveData](../iparagraphformateffectivedata/)\> [GetEffective](./geteffective/)() override | 取得套用繼承後的有效段落格式資料。 |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | 返回雜湊碼。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述的類型實例。相當於 C# 的 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂型別的複製。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷貝建構子。實際上不進行拷貝，只是初始化新物件並允許子類別的拷貝建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不進行拷貝，只是初始化新物件並允許子類別的拷貝建構。 |
|  [ParagraphFormat](./paragraphformat/)() | 初始化 [ParagraphFormat](./) 類別的新實例。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共用參考計數減少指定的值。 |
| void [set_Alignment](./set_alignment/)([TextAlignment](../textalignment/)) override | 設定段落中未套用繼承的文字對齊方式。寫入 [TextAlignment](../textalignment/)。 |
| void [set_DefaultTabSize](./set_defaulttabsize/)(**float**) override | 設定未套用繼承的預設定位大小。寫入 **float**。 |
| void [set_EastAsianLineBreak](./set_eastasianlinebreak/)([NullableBool](../nullablebool/)) override | 判斷段落是否使用東亞換行。未套用繼承。寫入 [NullableBool](../nullablebool/)。 |
| void [set_FontAlignment](./set_fontalignment/)([Aspose::Slides::FontAlignment](../fontalignment/)) override | 設定段落中未套用繼承的字體對齊方式。寫入 [Slides::FontAlignment](../fontalignment/)。 |
| void [set_HangingPunctuation](./set_hangingpunctuation/)([NullableBool](../nullablebool/)) override | 判斷段落是否使用懸掛標點。未套用繼承。寫入 [NullableBool](../nullablebool/)。 |
| void [set_Indent](./set_indent/)(**float**) override | 設定段落未套用繼承的首行縮排/懸掛縮排。懸掛縮排可使用負值定義。寫入 **float**。 |
| void [set_LatinLineBreak](./set_latinlinebreak/)([NullableBool](../nullablebool/)) override | 判斷段落是否使用拉丁換行。未套用繼承。寫入 [NullableBool](../nullablebool/)。 |
| void [set_MarginLeft](./set_marginleft/)(**float**) override | 設定段落未套用繼承的左邊距。寫入 **float**。 |
| void [set_MarginRight](./set_marginright/)(**float**) override | 設定段落未套用繼承的右邊距。寫入 **float**。 |
| void [set_RightToLeft](./set_righttoleft/)([NullableBool](../nullablebool/)) override | 判斷段落是否使用從右至左書寫。未套用繼承。寫入 [NullableBool](../nullablebool/)。 |
| void [set_SpaceAfter](./set_spaceafter/)(**float**) override | 設定段落未套用繼承的最後一行之後的空白量。正值指定空白的字型大小百分比，負值則以點數指定空白大小。寫入 **float**。 |
| void [set_SpaceBefore](./set_spacebefore/)(**float**) override | 設定段落未套用繼承的第一行之前的空白量。正值指定空白的字型大小百分比，負值則以點數指定空白大小。寫入 **float**。 |
| void [set_SpaceWithin](./set_spacewithin/)(**float**) override | 設定段落基線之間的空白量。正值表示百分比，負值表示點數大小。未套用繼承。寫入 **float**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 設定第 n 個模板參數為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得目前的共用參考計數值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共用參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共用參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構式。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 備註


此類別用於返回和操作針對特定段落定義的段落格式屬性。這表示在取得值時不會套用繼承，因此在大多數情況下您會得到表示「未定義」的值。

若要取得包含繼承的有效格式參數值，您需要使用 [ParagraphFormat::GetEffective](./geteffective/) 方法，該方法會返回一個 [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/) 實例。

## 另見

* 類別 [PVIObject](../pviobject/)
* 類別 [IParagraphFormat](../iparagraphformat/)
* 類別 [IChartParagraphFormat](../../aspose.slides.charts/ichartparagraphformat/)
* 命名空間 [Aspose::Slides](../)
* 程式庫 [Aspose.Slides](../../)