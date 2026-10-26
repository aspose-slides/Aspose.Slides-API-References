---
title: IParagraphFormat
second_title: Aspose.Slides for C++ API 參考文件
description: 此類別包含段落格式屬性。與 IParagraphFormatEffectiveData 不同，此類別的所有屬性皆可寫入。
type: docs
weight: 3147
url: /zh-hant/aspose.slides/iparagraphformat/
---
## IParagraphFormat 類別


此類別包含段落格式屬性。與 [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/) 不同，此類別的所有屬性皆可寫入。

```cpp
class IParagraphFormat : public virtual System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 與任何值（包括 NaN）皆不相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 與任何值（包括 NaN）皆不相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| virtual [TextAlignment](../textalignment/) [get_Alignment](./get_alignment/)() | 返回段落中未套用繼承的文字對齊方式。讀取 [TextAlignment](../textalignment/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormat](../ibulletformat/)\> [get_Bullet](./get_bullet/)() | 返回段落的項目符號格式。唯讀 [IBulletFormat](../ibulletformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormat](../iportionformat/)\> [get_DefaultPortionFormat](./get_defaultportionformat/)() | 返回段落的預設部分格式。未套用繼承。唯讀 [IPortionFormat](../iportionformat/)。 |
| virtual **float** [get_DefaultTabSize](./get_defaulttabsize/)() | 返回未套用繼承的預設定位大小。讀取 **float**。 |
| virtual **int16_t** [get_Depth](./get_depth/)() | 返回段落的深度。值 0 表示未定義的值。讀取 **int16_t**。 |
| virtual [NullableBool](../nullablebool/) [get_EastAsianLineBreak](./get_eastasianlinebreak/)() | 判斷段落是否使用東亞斷行。未套用繼承。讀取 [NullableBool](../nullablebool/)。 |
| virtual [Aspose::Slides::FontAlignment](../fontalignment/) [get_FontAlignment](./get_fontalignment/)() | 返回段落中未套用繼承的字型對齊方式。讀取 [Slides::FontAlignment](../fontalignment/)。 |
| virtual [NullableBool](../nullablebool/) [get_HangingPunctuation](./get_hangingpunctuation/)() | 判斷段落是否使用懸掛標點。未套用繼承。讀取 [NullableBool](../nullablebool/)。 |
| virtual **float** [get_Indent](./get_indent/)() | 返回段落的首行縮排/懸掛縮排，未套用繼承。懸掛縮排可使用負值定義。讀取 **float**。 |
| virtual [NullableBool](../nullablebool/) [get_LatinLineBreak](./get_latinlinebreak/)() | 判斷段落是否使用拉丁斷行。未套用繼承。讀取 [NullableBool](../nullablebool/)。 |
| virtual **float** [get_MarginLeft](./get_marginleft/)() | 返回段落未套用繼承的左邊距。讀取 **float**。 |
| virtual **float** [get_MarginRight](./get_marginright/)() | 返回段落未套用繼承的右邊距。讀取 **float**。 |
| virtual [NullableBool](../nullablebool/) [get_RightToLeft](./get_righttoleft/)() | 判斷段落是否使用從右至左書寫。未套用繼承。讀取 [NullableBool](../nullablebool/)。 |
| virtual **float** [get_SpaceAfter](./get_spaceafter/)() | 返回段落未套用繼承的最後一行之後的空間量。正值指定應為字型大小的百分比。負值則以點數指定空白的大小。讀取 **float**。 |
| virtual **float** [get_SpaceBefore](./get_spacebefore/)() | 返回段落未套用繼承的第一行之前的空間量。正值指定應為字型大小的百分比。負值則以點數指定空白的大小。讀取 **float**。 |
| virtual **float** [get_SpaceWithin](./get_spacewithin/)() | 返回段落的基線之間的空間量。正值表示百分比，負值表示點數大小。未套用繼承。讀取 **float**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITab](../itab/)\> [get_Tab](./get_tab/)(**int32_t**) | 返回指定索引處段落的定位。未套用繼承。唯讀 [Aspose::Slides::ITab](../itab/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITabCollection](../itabcollection/)\> [get_Tabs](./get_tabs/)() | 返回段落的定位。未套用繼承。唯讀 [ITabCollection](../itabcollection/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormatEffectiveData](../iparagraphformateffectivedata/)\> [GetEffective](./geteffective/)() | 取得已套用繼承的有效段落格式資料。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。支援自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。相當於 C# 的 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 哨兵物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。支援自訂類型的複製。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構函式。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 賦值運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串與 nullptr 情況下的特殊化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串情況下的特殊化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 依指定值減少共享參考計數。 |
| virtual void [set_Alignment](./set_alignment/)([TextAlignment](../textalignment/)) | 設定段落未套用繼承的文字對齊方式。寫入 [TextAlignment](../textalignment/)。 |
| virtual void [set_DefaultTabSize](./set_defaulttabsize/)(**float**) | 設定未套用繼承的預設定位大小。寫入 **float**。 |
| virtual void [set_Depth](./set_depth/)(**int16_t**) | 設定段落的深度。值 0 表示未定義的值。寫入 **int16_t**。 |
| virtual void [set_EastAsianLineBreak](./set_eastasianlinebreak/)([NullableBool](../nullablebool/)) | 判斷段落是否使用東亞斷行。未套用繼承。寫入 [NullableBool](../nullablebool/)。 |
| virtual void [set_FontAlignment](./set_fontalignment/)([Aspose::Slides::FontAlignment](../fontalignment/)) | 設定段落未套用繼承的字型對齊方式。寫入 [Slides::FontAlignment](../fontalignment/)。 |
| virtual void [set_HangingPunctuation](./set_hangingpunctuation/)([NullableBool](../nullablebool/)) | 判斷段落是否使用懸掛標點。未套用繼承。寫入 [NullableBool](../nullablebool/)。 |
| virtual void [set_Indent](./set_indent/)(**float**) | 設定段落的首行縮排/懸掛縮排，未套用繼承。懸掛縮排可用負值定義。寫入 **float**。 |
| virtual void [set_LatinLineBreak](./set_latinlinebreak/)([NullableBool](../nullablebool/)) | 判斷段落是否使用拉丁斷行。未套用繼承。寫入 [NullableBool](../nullablebool/)。 |
| virtual void [set_MarginLeft](./set_marginleft/)(**float**) | 設定段落未套用繼承的左邊距。寫入 **float**。 |
| virtual void [set_MarginRight](./set_marginright/)(**float**) | 設定段落未套用繼承的右邊距。寫入 **float**。 |
| virtual void [set_RightToLeft](./set_righttoleft/)([NullableBool](../nullablebool/)) | 判斷段落是否使用從右至左書寫。未套用繼承。寫入 [NullableBool](../nullablebool/)。 |
| virtual void [set_SpaceAfter](./set_spaceafter/)(**float**) | 設定段落未套用繼承的最後一行之後的空間量。正值指定應為字型大小的百分比。負值指定點數大小。寫入 **float**。 |
| virtual void [set_SpaceBefore](./set_spacebefore/)(**float**) | 設定段落未套用繼承的第一行之前的空間量。正值指定應為字型大小的百分比。負值指定點數大小。寫入 **float**。 |
| virtual void [set_SpaceWithin](./set_spacewithin/)(**float**) | 設定段落的基線之間的空間量。正值表示百分比，負值表示點數大小。未套用繼承。寫入 **float**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 設定第 n 個模板參數為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改使用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並返回共享參考計數。不應直接呼叫；請改使用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。支援將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 哨兵物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改使用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改使用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |
## 備註


此類別用於返回和操作特定段落定義的段落格式屬性。這表示在取得值時不會套用繼承，因此在大多數情況下會取得「未定義」的值。

為了取得包括繼承在內的有效格式參數值，您需要使用 [IParagraphFormat::GetEffective](./geteffective/) 方法，該方法返回 [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/) 實例。
## 另請參閱

* 類別 [Object](../../system/object/)
* 命名空間 [Aspose::Slides](../)
* 函式庫 [Aspose.Slides](../../)