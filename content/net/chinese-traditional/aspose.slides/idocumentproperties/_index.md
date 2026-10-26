---
title: IDocumentProperties
second_title: Aspose.Sildes for .NET API 參考
description: 表示簡報的屬性。
type: docs
weight: 5710
url: /zh-hant/aspose.slides/idocumentproperties/
---
## IDocumentProperties 介面

表示簡報的屬性。

```csharp
public interface IDocumentProperties
```

## 屬性

| 名稱 | 說明 |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/idocumentproperties/applicationtemplate) { get; set; } | 返回或設定應用程式的範本。讀寫 String。 |
| [AppVersion](../../aspose.slides/idocumentproperties/appversion) { get; } | 返回應用程式版本。唯讀 String。 |
| [Author](../../aspose.slides/idocumentproperties/author) { get; set; } | 返回或設定簡報的作者。讀寫 String。 |
| [Category](../../aspose.slides/idocumentproperties/category) { get; set; } | 返回或設定簡報的類別。讀寫 String。 |
| [Comments](../../aspose.slides/idocumentproperties/comments) { get; set; } | 返回或設定簡報的註解。讀寫 String。 |
| [Company](../../aspose.slides/idocumentproperties/company) { get; set; } | 返回或設定公司屬性。讀寫 String。 |
| [ContentStatus](../../aspose.slides/idocumentproperties/contentstatus) { get; set; } | 返回或設定簡報的內容狀態。讀寫 String。 |
| [ContentType](../../aspose.slides/idocumentproperties/contenttype) { get; set; } | 返回或設定簡報的內容類型。讀寫 String。 |
| [CountOfCustomProperties](../../aspose.slides/idocumentproperties/countofcustomproperties) { get; } | 返回集合中實際包含的自訂屬性數量。唯讀 Int32。 |
| [CreatedTime](../../aspose.slides/idocumentproperties/createdtime) { get; set; } | 返回簡報建立的日期。值以 UTC 為單位。讀寫 DateTime。 |
| [HeadingPairs](../../aspose.slides/idocumentproperties/headingpairs) { get; } | 指示文件部分的分組及每個群組中的部分數量。唯讀 IHeadingPair[]。 |
| [HiddenSlides](../../aspose.slides/idocumentproperties/hiddenslides) { get; } | 指定簡報文件中隱藏投影片的數量。唯讀 Int32。 |
| [HyperlinkBase](../../aspose.slides/idocumentproperties/hyperlinkbase) { get; set; } | 返回或設定 HyperlinkBase 文件屬性。讀寫 String。 |
| [HyperlinksChanged](../../aspose.slides/idocumentproperties/hyperlinkschanged) { get; set; } | 指定此部分中的一個或多個超連結僅由產生者在此部分中更新。下一個開啟此文件的產生者應使用此部分中指定的新超連結更新超連結關係。讀寫 Boolean。 |
| [Item](../../aspose.slides/idocumentproperties/item) { get; set; } | 返回或設定與指定名稱相關聯的自訂屬性。讀寫 Object。 |
| [Keywords](../../aspose.slides/idocumentproperties/keywords) { get; set; } | 返回或設定簡報的關鍵字。讀寫 String。 |
| [LastPrinted](../../aspose.slides/idocumentproperties/lastprinted) { get; set; } | 返回簡報上次列印的日期。讀寫 DateTime。 |
| [LastSavedBy](../../aspose.slides/idocumentproperties/lastsavedby) { get; set; } | 返回或設定最後修改簡報之人的名稱。讀寫 String。 |
| [LastSavedTime](../../aspose.slides/idocumentproperties/lastsavedtime) { get; set; } | 返回簡報最後一次修改的日期。值以 UTC 為單位。在 Presentation.DocumentProperties 的情況下為唯讀（因為在 IPresentation 物件儲存過程中會內部更新）。可藉由方法 [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties) 回傳的 DocumentProperties 實例進行變更。請參閱 [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties) 方法摘要中的範例。 |
| [LinksUpToDate](../../aspose.slides/idocumentproperties/linksuptodate) { get; set; } | 指示文件中的超連結是否為最新。將此元素設為 **true** 以表示超連結已更新。將此元素設為 **false** 以表示超連結已過時。讀寫 Boolean。 |
| [Manager](../../aspose.slides/idocumentproperties/manager) { get; set; } | 返回或設定管理員屬性。讀寫 String。 |
| [MultimediaClips](../../aspose.slides/idocumentproperties/multimediaclips) { get; } | 指定文件中存在的聲音或影片剪輯的總數。唯讀 Int32。 |
| [NameOfApplication](../../aspose.slides/idocumentproperties/nameofapplication) { get; set; } | 返回或設定應用程式的名稱。讀寫 String。 |
| [Notes](../../aspose.slides/idocumentproperties/notes) { get; } | 指定簡報中包含備註的投影片數量。唯讀 Int32。 |
| [Paragraphs](../../aspose.slides/idocumentproperties/paragraphs) { get; } | 指定文件中（若適用）找到的段落總數。唯讀 Int32。 |
| [PresentationFormat](../../aspose.slides/idocumentproperties/presentationformat) { get; set; } | 返回或設定簡報的目標格式。讀寫 String。 |
| [RevisionNumber](../../aspose.slides/idocumentproperties/revisionnumber) { get; set; } | 返回或設定簡報的修訂號碼。讀寫 Int32。 |
| [ScaleCrop](../../aspose.slides/idocumentproperties/scalecrop) { get; set; } | 指示文件縮圖的顯示模式。將此元素設為 **true** 以啟用將文件縮圖縮放至顯示區。將此元素設為 **false** 以啟用裁剪文件縮圖，只顯示適合顯示區的部分。讀寫 Boolean。 |
| [SharedDoc](../../aspose.slides/idocumentproperties/shareddoc) { get; set; } | 確定簡報是否在多個使用者之間共享。讀寫 Boolean。 |
| [Slides](../../aspose.slides/idocumentproperties/slides) { get; } | 指定簡報文件中的投影片總數。唯讀 Int32。 |
| [Subject](../../aspose.slides/idocumentproperties/subject) { get; set; } | 返回或設定簡報的主題。讀寫 String。 |
| [Title](../../aspose.slides/idocumentproperties/title) { get; set; } | 返回或設定簡報的標題。讀寫 String。 |
| [TitlesOfParts](../../aspose.slides/idocumentproperties/titlesofparts) { get; } | 指定每個文件部分的標題。這些部分不是實際的文件部分，而是文件章節的概念性表示。唯讀 string[]。 |
| [TotalEditingTime](../../aspose.slides/idocumentproperties/totaleditingtime) { get; set; } | 簡報的總編輯時間。讀寫 TimeSpan。 |
| [Words](../../aspose.slides/idocumentproperties/words) { get; } | 指定文件中包含的總單字數。唯讀 Int32。 |

## 方法

| 名稱 | 說明 |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/idocumentproperties/clearbuiltinproperties)() | 清除並設定所有內建屬性的預設值。 |
| [ClearCustomProperties](../../aspose.slides/idocumentproperties/clearcustomproperties)() | 移除所有自訂屬性。 |
| [ContainsCustomProperty](../../aspose.slides/idocumentproperties/containscustomproperty)(string) | 檢查是否存在具有指定名稱的自訂屬性。 |
| [GetCustomPropertyName](../../aspose.slides/idocumentproperties/getcustompropertyname)(int) | 返回指定索引處的自訂屬性名稱。 |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | 從自訂屬性取得具名 Boolean 值。 |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | 從自訂屬性取得具名 DateTime 值。 |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | 從自訂屬性取得具名 double 值。 |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | 從自訂屬性取得具名 float 值。 |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | 從自訂屬性取得具名 integer 值。 |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | 從自訂屬性取得具名 string 值。 |
| [GetSensitivityLabels](../../aspose.slides/idocumentproperties/getsensitivitylabels)() | 從自訂文件屬性取得敏感度標籤陣列（Microsoft Information Protection SDK Metadata）。 |
| [RemoveCustomProperty](../../aspose.slides/idocumentproperties/removecustomproperty)(string) | 移除與指定名稱相關聯的自訂屬性。 |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | 設定具名 boolean 自訂屬性。 |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | 設定具名 DateTime 自訂屬性。 |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | 設定具名 double 自訂屬性。 |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | 設定具名 float 自訂屬性。 |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | 設定具名 integer 自訂屬性。 |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | 設定具名 string 自訂屬性。 |

### 另請參閱

* 命名空間 [Aspose.Slides](../../aspose.slides)
* 組件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->