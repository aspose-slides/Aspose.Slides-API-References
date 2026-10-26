---
title: IDocumentProperties
second_title: Aspose.Slides for C++ API 參考文件
description: 表示簡報的屬性。
type: docs
weight: 1977
url: /zh-hant/aspose.slides/idocumentproperties/
---
## IDocumentProperties 類別

表示簡報的屬性。

```cpp
class IDocumentProperties : public virtual System::Object
```

## 方法

| Method | Description |
| --- | --- |
| virtual void [ClearBuiltInProperties](./clearbuiltinproperties/)() | 清除並設定所有內建屬性的預設值。 |
| virtual void [ClearCustomProperties](./clearcustomproperties/)() | 移除所有自訂屬性。 |
| virtual **bool** [ContainsCustomProperty](./containscustomproperty/)([System::String](../../system/string/)) | 檢查是否存在具有指定名稱的自訂屬性。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使依 IEC 60559:1989 標準 NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使依 IEC 60559:1989 標準 NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| virtual [System::String](../../system/string/) [get_ApplicationTemplate](./get_applicationtemplate/)() | 傳回應用程式的範本。請參閱 [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_AppVersion](./get_appversion/)() | 傳回應用程式版本。唯讀 [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_Author](./get_author/)() | 傳回簡報的作者。請參閱 [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_Category](./get_category/)() | 傳回簡報的類別。請參閱 [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_Comments](./get_comments/)() | 傳回簡報的註解。請參閱 [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_Company](./get_company/)() | 傳回公司屬性。請參閱 [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_ContentStatus](./get_contentstatus/)() | 傳回簡報的內容狀態。請參閱 [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_ContentType](./get_contenttype/)() | 傳回簡報的內容類型。請參閱 [System::String](../../system/string/)。 |
| virtual **int32_t** [get_CountOfCustomProperties](./get_countofcustomproperties/)() | 傳回集合中實際包含的自訂屬性數量。唯讀 **int32_t**。 |
| virtual [System::DateTime](../../system/datetime/) [get_CreatedTime](./get_createdtime/)() | 傳回簡報的建立日期。值以 UTC 表示。請參閱 [System::DateTime](../../system/datetime/)。 |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IHeadingPair](../iheadingpair/)\>\> [get_HeadingPairs](./get_headingpairs/)() | 指示文件部件的分組及每組的部件數量。唯讀 [System::ArrayPtr<System::SharedPtr<IHeadingPair>>](../../system/arrayptr/)。 |
| virtual **int32_t** [get_HiddenSlides](./get_hiddenslides/)() | 指定簡報文件中隱藏投影片的數量。唯讀 **int32_t**。 |
| virtual [System::String](../../system/string/) [get_HyperlinkBase](./get_hyperlinkbase/)() | 傳回 HyperlinkBase 文件屬性。請參閱 [System::String](../../system/string/)。 |
| virtual **bool** [get_HyperlinksChanged](./get_hyperlinkschanged/)() | 指定此部件中的一個或多個超連結已由產生器僅在此部件中更新。下一個開啟此文件的產生器應使用此部件中指定的新超連結更新關係。唯讀 **bool**。 |
| virtual [System::String](../../system/string/) [get_Keywords](./get_keywords/)() | 傳回簡報的關鍵字。請參閱 [System::String](../../system/string/)。 |
| virtual [System::DateTime](../../system/datetime/) [get_LastPrinted](./get_lastprinted/)() | 傳回簡報上次列印的日期。請參閱 [System::DateTime](../../system/datetime/)。 |
| virtual [System::String](../../system/string/) [get_LastSavedBy](./get_lastsavedby/)() | 傳回最後修改簡報的人的名稱。請參閱 [System::String](../../system/string/)。 |
| virtual [System::DateTime](../../system/datetime/) [get_LastSavedTime](./get_lastsavedtime/)() | 傳回簡報最後修改的日期。值以 UTC 表示。若為 Presentation.DocumentProperties，則為唯讀（因為在 [IPresentation](../ipresentation/) 物件儲存過程中會內部更新）。可透過 [DocumentProperties](../documentproperties/) 實例（由 [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/) 方法返回）進行變更。請參閱 [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/) 方法摘要中的範例。 |
| virtual **bool** [get_LinksUpToDate](./get_linksuptodate/)() | 指示文件中的超連結是否為最新。將此元素設定為 **true** 以表示超連結已更新。將此元素設定為 **false** 以表示超連結已過時。唯讀 **bool**。 |
| virtual [System::String](../../system/string/) [get_Manager](./get_manager/)() | 傳回管理者屬性。請參閱 [System::String](../../system/string/)。 |
| virtual **int32_t** [get_MultimediaClips](./get_multimediaclips/)() | 指定文件中存在的聲音或影片剪輯的總數。唯讀 **int32_t**。 |
| virtual [System::String](../../system/string/) [get_NameOfApplication](./get_nameofapplication/)() | 傳回應用程式的名稱。請參閱 [System::String](../../system/string/)。 |
| virtual **int32_t** [get_Notes](./get_notes/)() | 指定含有註記的簡報投影片數量。唯讀 **int32_t**。 |
| virtual **int32_t** [get_Paragraphs](./get_paragraphs/)() | 指定文件中（如適用）找到的段落總數。唯讀 **int32_t**。 |
| virtual [System::String](../../system/string/) [get_PresentationFormat](./get_presentationformat/)() | 傳回簡報的預期格式。請參閱 [System::String](../../system/string/)。 |
| virtual **int32_t** [get_RevisionNumber](./get_revisionnumber/)() | 傳回簡報的版本號碼。唯讀 **int32_t**。 |
| virtual **bool** [get_ScaleCrop](./get_scalecrop/)() | 指示文件縮圖的顯示模式。將此元素設定為 **true** 以啟用縮圖依顯示器縮放。將此元素設定為 **false** 以啟用裁剪，只顯示符合顯示器的區段。唯讀 **bool**。 |
| virtual **bool** [get_SharedDoc](./get_shareddoc/)() | 判斷簡報是否在多個人之間共享。唯讀 **bool**。 |
| virtual **int32_t** [get_Slides](./get_slides/)() | 指定簡報文件中的投影片總數。唯讀 **int32_t**。 |
| virtual [System::String](../../system/string/) [get_Subject](./get_subject/)() | 傳回簡報的主旨。請參閱 [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_Title](./get_title/)() | 傳回簡報的標題。請參閱 [System::String](../../system/string/)。 |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_TitlesOfParts](./get_titlesofparts/)() | 指定每個文件部件的標題。這些部件並非文件部件，而是文件區段的概念性表示。唯讀 [System::ArrayPtr<System::String>](../../system/arrayptr/)。 |
| virtual [System::TimeSpan](../../system/timespan/) [get_TotalEditingTime](./get_totaleditingtime/)() | 簡報的總編輯時間。請參閱 [System::TimeSpan](../../system/timespan/)。 |
| virtual **int32_t** [get_Words](./get_words/)() | 指定文件中包含的單詞總數。唯讀 **int32_t**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| virtual [System::String](../../system/string/) [GetCustomPropertyName](./getcustompropertyname/)(**int32_t**) | 在指定索引處返回自訂屬性名稱。 |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **bool**\&) | 從自訂屬性取得具名布林值。 |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **int32_t**\&) | 從自訂屬性取得具名整數值。 |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)\&) | 從自訂屬性取得具名 DateTime 值。 |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)\&) | 從自訂屬性取得具名字串值。 |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **float**\&) | 從自訂屬性取得具名浮點數值。 |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **double**\&) | 從自訂屬性取得具名 double 值。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISensitivityLabel](../isensitivitylabel/)\>\> [GetSensitivityLabels](./getsensitivitylabels/)() | 從自訂文件屬性取得敏感度標籤陣列（Microsoft Information Protection SDK 中繼資料）。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [idx_get](./idx_get/)([System::String](../../system/string/)) | 傳回與指定名稱相關聯的自訂屬性。請參閱 [System::Object](../../system/object/)。 |
| virtual void [idx_set](./idx_set/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | 設定與指定名稱相關聯的自訂屬性。寫入 [System::Object](../../system/object/)。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。相當於 C# 的 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂類型的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷貝建構子。實際上不複製任何內容，只是初始化新物件，並允許子類別的拷貝建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不複製任何內容，只是初始化新物件，並允許子類別的拷貝建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 將值型別物件與 nullptr 以參考方式比較。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 針對字串與 nullptr 情況的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 針對字串情況的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| virtual **bool** [RemoveCustomProperty](./removecustomproperty/)([System::String](../../system/string/)) | 移除與指定名稱相關聯的自訂屬性。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定值。 |
| virtual void [set_ApplicationTemplate](./set_applicationtemplate/)([System::String](../../system/string/)) | 設定應用程式的範本。寫入 [System::String](../../system/string/)。 |
| virtual void [set_Author](./set_author/)([System::String](../../system/string/)) | 設定簡報的作者。寫入 [System::String](../../system/string/)。 |
| virtual void [set_Category](./set_category/)([System::String](../../system/string/)) | 設定簡報的類別。寫入 [System::String](../../system/string/)。 |
| virtual void [set_Comments](./set_comments/)([System::String](../../system/string/)) | 設定簡報的註解。寫入 [System::String](../../system/string/)。 |
| virtual void [set_Company](./set_company/)([System::String](../../system/string/)) | 設定公司屬性。寫入 [System::String](../../system/string/)。 |
| virtual void [set_ContentStatus](./set_contentstatus/)([System::String](../../system/string/)) | 設定簡報的內容狀態。寫入 [System::String](../../system/string/)。 |
| virtual void [set_ContentType](./set_contenttype/)([System::String](../../system/string/)) | 設定簡報的內容類型。寫入 [System::String](../../system/string/)。 |
| virtual void [set_CreatedTime](./set_createdtime/)([System::DateTime](../../system/datetime/)) | 傳回簡報的建立日期。值以 UTC 表示。寫入 [System::DateTime](../../system/datetime/)。 |
| virtual void [set_HyperlinkBase](./set_hyperlinkbase/)([System::String](../../system/string/)) | 設定 HyperlinkBase 文件屬性。寫入 [System::String](../../system/string/)。 |
| virtual void [set_HyperlinksChanged](./set_hyperlinkschanged/)(**bool**) | 指定此部件中的一個或多個超連結已由產生器僅在此部件中更新。下一個開啟此文件的產生器應使用此部件中指定的新超連結更新關係。寫入 **bool**。 |
| virtual void [set_Keywords](./set_keywords/)([System::String](../../system/string/)) | 設定簡報的關鍵字。寫入 [System::String](../../system/string/)。 |
| virtual void [set_LastPrinted](./set_lastprinted/)([System::DateTime](../../system/datetime/)) | 傳回簡報上次列印的日期。寫入 [System::DateTime](../../system/datetime/)。 |
| virtual void [set_LastSavedBy](./set_lastsavedby/)([System::String](../../system/string/)) | 設定最後修改簡報的人的名稱。寫入 [System::String](../../system/string/)。 |
| virtual void [set_LastSavedTime](./set_lastsavedtime/)([System::DateTime](../../system/datetime/)) | 傳回簡報最後修改的日期。值以 UTC 表示。若為 Presentation.DocumentProperties，則為唯讀（因為在 [IPresentation](../ipresentation/) 物件儲存過程中會內部更新）。可透過 [DocumentProperties](../documentproperties/) 實例（由 [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/) 方法返回）進行變更。請參閱 [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/) 方法摘要中的範例。 |
| virtual void [set_LinksUpToDate](./set_linksuptodate/)(**bool**) | 指示文件中的超連結是否為最新。將此元素設定為 **true** 以表示超連結已更新。將此元素設定為 **false** 以表示超連結已過時。寫入 **bool**。 |
| virtual void [set_Manager](./set_manager/)([System::String](../../system/string/)) | 設定管理者屬性。寫入 [System::String](../../system/string/)。 |
| virtual void [set_NameOfApplication](./set_nameofapplication/)([System::String](../../system/string/)) | 設定應用程式的名稱。寫入 [System::String](../../system/string/)。 |
| virtual void [set_PresentationFormat](./set_presentationformat/)([System::String](../../system/string/)) | 設定簡報的預期格式。寫入 [System::String](../../system/string/)。 |
| virtual void [set_RevisionNumber](./set_revisionnumber/)(**int32_t**) | 設定簡報的版本號碼。寫入 **int32_t**。 |
| virtual void [set_ScaleCrop](./set_scalecrop/)(**bool**) | 指示文件縮圖的顯示模式。將此元素設定為 **true** 以啟用縮圖依顯示器縮放。將此元素設定為 **false** 以啟用裁剪，只顯示符合顯示器的區段。寫入 **bool**。 |
| virtual void [set_SharedDoc](./set_shareddoc/)(**bool**) | 判斷簡報是否在多個人之間共享。寫入 **bool**。 |
| virtual void [set_Subject](./set_subject/)([System::String](../../system/string/)) | 設定簡報的主旨。寫入 [System::String](../../system/string/)。 |
| virtual void [set_Title](./set_title/)([System::String](../../system/string/)) | 設定簡報的標題。寫入 [System::String](../../system/string/)。 |
| virtual void [set_TotalEditingTime](./set_totaleditingtime/)([System::TimeSpan](../../system/timespan/)) | 簡報的總編輯時間。寫入 [System::TimeSpan](../../system/timespan/)。 |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **bool**) | 設定具名布林自訂屬性。 |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **int32_t**) | 設定具名整數自訂屬性。 |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)) | 設定具名 DateTime 自訂屬性。 |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)) | 設定具名字串自訂屬性。 |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **float**) | 設定具名浮點數自訂屬性。 |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **double**) | 設定具名 double 自訂屬性。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 設定第 n 個範本參數為弱指標（而非共享）。允許在容器中切換指標為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫，請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減且返回共享參考計數。不應直接呼叫，請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫，請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫，請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另請參閱

* 類別 [Object](../../system/object/)
* 命名空間 [Aspose::Slides](../)
* 函式庫 [Aspose.Slides](../../)