---
title: DocumentProperties
second_title: Aspose.Slides 用於 C++ 的 API 參考
description: 表示簡報的屬性。
type: docs
weight: 794
url: /zh-hant/aspose.slides/documentproperties/
---
## DocumentProperties 類別

表示簡報的屬性。

```cpp
class DocumentProperties : public Aspose::Slides::IDocumentProperties,
                           public Aspose::Slides::IGenericCloneable<System::SharedPtr<Aspose::Slides::IDocumentProperties>>
```

## 方法

| 方法 | 說明 |
| --- | --- |
| void [ClearBuiltInProperties](./clearbuiltinproperties/)() override | 清除並為所有內建屬性設定預設值。 |
| void [ClearCustomProperties](./clearcustomproperties/)() override | 移除所有自訂屬性。 |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [Clone](./clone/)() override | 複製目前物件 |
| [System::SharedPtr](../../system/sharedptr/)\<[IDocumentProperties](../idocumentproperties/)\> [CloneT](./clonet/)() override | 複製目前物件 |
| **bool** [ContainsCustomProperty](./containscustomproperty/)([System::String](../../system/string/)) override | 檢查是否存在指定名稱的自訂屬性。 |
|  [DocumentProperties](./documentproperties/)() | 初始化 [DocumentProperties](./) 類別的新執行個體。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 與任何值（包括 NaN）皆不相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 與任何值（包括 NaN）皆不相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| [System::String](../../system/string/) [get_ApplicationTemplate](./get_applicationtemplate/)() override | 回傳應用程式的範本。請參閱 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_AppVersion](./get_appversion/)() override | 回傳應用程式版本。唯讀 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_Author](./get_author/)() override | 回傳簡報的作者。請參閱 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_Category](./get_category/)() override | 回傳簡報的類別。請參閱 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_Comments](./get_comments/)() override | 回傳簡報的註解。請參閱 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_Company](./get_company/)() override | 回傳公司屬性。請參閱 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_ContentStatus](./get_contentstatus/)() override | 回傳簡報的內容狀態。請參閱 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_ContentType](./get_contenttype/)() override | 回傳簡報的內容類型。請參閱 [System::String](../../system/string/)。 |
| **int32_t** [get_CountOfCustomProperties](./get_countofcustomproperties/)() override | 回傳集合中實際包含的自訂屬性數量。唯讀 **int32_t**。 |
| [System::DateTime](../../system/datetime/) [get_CreatedTime](./get_createdtime/)() override | 回傳簡報建立的日期。值為 UTC。請參閱 [System::DateTime](../../system/datetime/)。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IHeadingPair](../iheadingpair/)\>\> [get_HeadingPairs](./get_headingpairs/)() override | 指出文件部分的分組以及每組的部分數量。唯讀 [System::ArrayPtr<System::SharedPtr<IHeadingPair>>](../../system/arrayptr/)。 |
| **int32_t** [get_HiddenSlides](./get_hiddenslides/)() override | 回傳簡報文件中隱藏投影片的數量。唯讀 **int32_t**。 |
| [System::String](../../system/string/) [get_HyperlinkBase](./get_hyperlinkbase/)() override | 回傳 HyperlinkBase 文件屬性。請參閱 [System::String](../../system/string/)。 |
| **bool** [get_HyperlinksChanged](./get_hyperlinkschanged/)() override | 指定此部分中的一或多個超連結已由製作者僅在此部分更新。下一位開啟此文件的製作者應使用此部分指定的新超連結更新超連結關係。唯讀 **bool**。 |
| [System::String](../../system/string/) [get_Keywords](./get_keywords/)() override | 回傳簡報的關鍵字。請參閱 [System::String](../../system/string/)。 |
| [System::DateTime](../../system/datetime/) [get_LastPrinted](./get_lastprinted/)() override | 回傳簡報最近一次列印的日期。請參閱 [System::DateTime](../../system/datetime/)。 |
| [System::String](../../system/string/) [get_LastSavedBy](./get_lastsavedby/)() override | 回傳最後修改簡報之人的姓名。請參閱 [System::String](../../system/string/)。 |
| [System::DateTime](../../system/datetime/) [get_LastSavedTime](./get_lastsavedtime/)() override | 回傳簡報最後修改的日期。值為 UTC。若為 [Presentation::get_DocumentProperties](../presentation/get_documentproperties/) 時為唯讀（因為在 [IPresentation](../ipresentation/) 物件儲存過程中會內部更新）。可透過方法 [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/) 回傳的 [DocumentProperties](./) 實例進行變更。請參閱 [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/) 方法摘要中的範例。 |
| **bool** [get_LinksUpToDate](./get_linksuptodate/)() override | 指示文件中的超連結是否為最新。將此元素設為 **true** 表示超連結已更新。將此元素設為 **false** 表示超連結已過時。唯讀 **bool**。 |
| [System::String](../../system/string/) [get_Manager](./get_manager/)() override | 回傳管理員屬性。請參閱 [System::String](../../system/string/)。 |
| **int32_t** [get_MultimediaClips](./get_multimediaclips/)() override | 回傳文件中存在的音訊或影片剪輯的總數量。唯讀 **int32_t**。 |
| [System::String](../../system/string/) [get_NameOfApplication](./get_nameofapplication/)() override | 回傳應用程式的名稱。請參閱 [System::String](../../system/string/)。 |
| **int32_t** [get_Notes](./get_notes/)() override | 回傳包含備註的簡報投影片數量。唯讀 **int32_t**。 |
| **int32_t** [get_Paragraphs](./get_paragraphs/)() override | 回傳文件中（若適用）段落的總數量。唯讀 **int32_t**。 |
| [System::String](../../system/string/) [get_PresentationFormat](./get_presentationformat/)() override | 回傳簡報的預期格式。請參閱 [System::String](../../system/string/)。 |
| **int32_t** [get_RevisionNumber](./get_revisionnumber/)() override | 回傳簡報的修訂號。唯讀 **int32_t**。 |
| **bool** [get_ScaleCrop](./get_scalecrop/)() override | 指示文件縮圖的顯示模式。將此元素設為 **true** 可讓縮圖縮放至顯示區。將此元素設為 **false** 可讓縮圖裁剪僅顯示適合顯示區的部分。唯讀 **bool**。 |
| **bool** [get_SharedDoc](./get_shareddoc/)() override | 判斷簡報是否在多位使用者之間共享。唯讀 **bool**。 |
| **int32_t** [get_Slides](./get_slides/)() override | 回傳簡報文件中的投影片總數。唯讀 **int32_t**。 |
| [System::String](../../system/string/) [get_Subject](./get_subject/)() override | 回傳簡報的主旨。請參閱 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_Title](./get_title/)() override | 回傳簡報的標題。請參閱 [System::String](../../system/string/)。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_TitlesOfParts](./get_titlesofparts/)() override | 指定每個文件部分的標題。這些部分不是實際文件部分，而是文件段落的概念性表示。唯讀 [System::ArrayPtr<System::String>](../../system/arrayptr/)。 |
| [System::TimeSpan](../../system/timespan/) [get_TotalEditingTime](./get_totaleditingtime/)() override | 回傳簡報的總編輯時間。請參閱 [System::TimeSpan](../../system/timespan/)。 |
| **int32_t** [get_Words](./get_words/)() override | 回傳文件中包含的字數總計。唯讀 **int32_t**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數器資料結構。 |
| [System::String](../../system/string/) [GetCustomPropertyName](./getcustompropertyname/)(**int32_t**) override | 在指定索引處返回自訂屬性名稱。 |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **bool**\&) override | 從自訂屬性取得具名布林值。 |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **int32_t**\&) override | 從自訂屬性取得具名整數值。 |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)\&) override | 從自訂屬性取得具名 DateTime 值。 |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)\&) override | 從自訂屬性取得具名字串值。 |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **float**\&) override | 從自訂屬性取得具名 float 值。 |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **double**\&) override | 從自訂層取得具名 double 值。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISensitivityLabel](../isensitivitylabel/)\>\> [GetSensitivityLabels](./getsensitivitylabels/)() override | 從自訂文件屬性取得敏感度標籤陣列（Microsoft Information Protection SDK Metadata）。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [idx_get](./idx_get/)([System::String](../../system/string/)) override | 回傳與指定名稱相關聯的自訂屬性。請參閱 [System::Object](../../system/object/)。 |
| void [idx_set](./idx_set/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 設定與指定名稱相關聯的自訂屬性。寫入 [System::Object](../../system/object/)。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。相當於 C# 的 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 哨兵物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂類型的複製。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。事實上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 賦值運算子。事實上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串與 nullptr 情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串情況。 |
| **bool** [RemoveCustomProperty](./removecustomproperty/)([System::String](../../system/string/)) override | 移除與指定名稱相關聯的自訂屬性。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 依指定值減少共享參考計數。 |
| void [set_ApplicationTemplate](./set_applicationtemplate/)([System::String](../../system/string/)) override | 設定應用程式的範本。寫入 [System::String](../../system/string/)。 |
| void [set_Author](./set_author/)([System::String](../../system/string/)) override | 設定簡報的作者。寫入 [System::String](../../system/string/)。 |
| void [set_Category](./set_category/)([System::String](../../system/string/)) override | 設定簡報的類別。寫入 [System::String](../../system/string/)。 |
| void [set_Comments](./set_comments/)([System::String](../../system/string/)) override | 設定簡報的註解。寫入 [System::String](../../system/string/)。 |
| void [set_Company](./set_company/)([System::String](../../system/string/)) override | 設定公司屬性。寫入 [System::String](../../system/string/)。 |
| void [set_ContentStatus](./set_contentstatus/)([System::String](../../system/string/)) override | 設定簡報的內容狀態。寫入 [System::String](../../system/string/)。 |
| void [set_ContentType](./set_contenttype/)([System::String](../../system/string/)) override | 設定簡報的內容類型。寫入 [System::String](../../system/string/)。 |
| void [set_CreatedTime](./set_createdtime/)([System::DateTime](../../system/datetime/)) override | 回傳簡報建立的日期。值為 UTC。寫入 [System::DateTime](../../system/datetime/)。 |
| void [set_HyperlinkBase](./set_hyperlinkbase/)([System::String](../../system/string/)) override | 設定 HyperlinkBase 文件屬性。寫入 [System::String](../../system/string/)。 |
| void [set_HyperlinksChanged](./set_hyperlinkschanged/)(**bool**) override | 指定此部分中的一或多個超連結已由製作者僅在此部分更新。下一位開啟此文件的製作者應使用此部分指定的新超連結更新超連結關係。寫入 **bool**。 |
| void [set_Keywords](./set_keywords/)([System::String](../../system/string/)) override | 設定簡報的關鍵字。寫入 [System::String](../../system/string/)。 |
| void [set_LastPrinted](./set_lastprinted/)([System::DateTime](../../system/datetime/)) override | 回傳簡報最近一次列印的日期。寫入 [System::DateTime](../../system/datetime/)。 |
| void [set_LastSavedBy](./set_lastsavedby/)([System::String](../../system/string/)) override | 設定最後修改簡報之人的姓名。寫入 [System::String](../../system/string/)。 |
| void [set_LastSavedTime](./set_lastsavedtime/)([System::DateTime](../../system/datetime/)) override | 回傳簡報最後一次修改的日期。值為 UTC。若為 [Presentation::get_DocumentProperties](../presentation/get_documentproperties/) 時為唯讀（因為在 [IPresentation](../ipresentation/) 物件儲存過程中會內部更新）。可透過方法 [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/) 回傳的 [DocumentProperties](./) 實例進行變更。請參閱 [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/) 方法摘要中的範例。 |
| void [set_LinksUpToDate](./set_linksuptodate/)(**bool**) override | 指示文件中的超連結是否為最新。將此元素設為 **true** 表示已更新。將此元素設為 **false** 表示已過時。寫入 **bool**。 |
| void [set_Manager](./set_manager/)([System::String](../../system/string/)) override | 設定管理員屬性。寫入 [System::String](../../system/string/)。 |
| void [set_NameOfApplication](./set_nameofapplication/)([System::String](../../system/string/)) override | 設定應用程式名稱。寫入 [System::String](../../system/string/)。 |
| void [set_PresentationFormat](./set_presentationformat/)([System::String](../../system/string/)) override | 設定簡報的預期格式。寫入 [System::String](../../system/string/)。 |
| void [set_RevisionNumber](./set_revisionnumber/)(**int32_t**) override | 設定簡報的修訂號。寫入 **int32_t**。 |
| void [set_ScaleCrop](./set_scalecrop/)(**bool**) override | 指示文件縮圖的顯示模式。將此元素設為 **true** 可讓縮圖縮放至顯示區。將此元素設為 **false** 可讓縮圖裁剪僅顯示適合顯示區的部分。寫入 **bool**。 |
| void [set_SharedDoc](./set_shareddoc/)(**bool**) override | 判斷簡報是否在多位使用者之間共享。寫入 **bool**。 |
| void [set_Subject](./set_subject/)([System::String](../../system/string/)) override | 設定簡報的主旨。寫入 [System::String](../../system/string/)。 |
| void [set_Title](./set_title/)([System::String](../../system/string/)) override | 設定簡報的標題。寫入 [System::String](../../system/string/)。 |
| void [set_TotalEditingTime](./set_totaleditingtime/)([System::TimeSpan](../../system/timespan/)) override | 設定簡報的總編輯時間。寫入 [System::TimeSpan](../../system/timespan/)。 |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **bool**) override | 設定具名布林自訂屬性。 |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **int32_t**) override | 設定具名整數自訂屬性。 |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)) override | 設定具名 DateTime 自訂屬性。 |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)) override | 設定具名字串自訂屬性。 |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **float**) override | 設定具名 float 自訂屬性。 |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **double**) override | 設定具名 double 自訂屬性。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 設定第 n 個範本參數為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數器的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並返回共享參考計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解除鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 哨兵物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 備註

以下範例說明如何存取 PowerPoint [Presentation](../presentation/) 的內建屬性。
```cpp
// 實例化表示簡報的 Presentation 類別
auto pres = System::MakeObject<Presentation>(dataDir + u"AccessBuiltin Properties.pptx");

// Create a reference to IDocumentProperties object associated with Presentation
System::SharedPtr<IDocumentProperties> documentProperties = pres->get_DocumentProperties();
// Display the builtin properties
System::Console::WriteLine(System::String(u"Category : ") + documentProperties->get_Category());
System::Console::WriteLine(System::String(u"Current Status : ") + documentProperties->get_ContentStatus());
System::Console::WriteLine(System::String(u"Creation Date : ") + documentProperties->get_CreatedTime());
System::Console::WriteLine(System::String(u"Author : ") + documentProperties->get_Author());
System::Console::WriteLine(System::String(u"Description : ") + documentProperties->get_Comments());
```
以下範例說明如何修改 PowerPoint [Presentation](../presentation/) 的內建屬性。
```cpp
// 實例化表示簡報的 Presentation 類別
auto presentation = System::MakeObject<Presentation>(dataDir + u"ModifyBuiltinProperties.pptx");

// 建立與 Presentation 相關聯的 IDocumentProperties 物件參考
System::SharedPtr<IDocumentProperties> documentProperties = presentation->get_DocumentProperties();
// 設定內建屬性
documentProperties->set_Author(u"Aspose.Slides for .NET");
documentProperties->set_Title(u"Modifying Presentation Properties");
documentProperties->set_Subject(u"Aspose Subject");
// 將簡報儲存至檔案
presentation->Save(u"DocumentProperties_out.pptx", SaveFormat::Pptx);
```

## 另見

* 類別 [IDocumentProperties](../idocumentproperties/)
* 類別 [IGenericCloneable](../igenericcloneable/)
* 名稱空間 [Aspose::Slides](../)
* 函式庫 [Aspose.Slides](../../)