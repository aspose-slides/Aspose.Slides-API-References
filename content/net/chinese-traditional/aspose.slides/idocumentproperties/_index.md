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
| [ApplicationTemplate](../../aspose.slides/idocumentproperties/applicationtemplate) { get; set; } | 返回或設定應用程式的範本。讀/寫 String。 |
| [AppVersion](../../aspose.slides/idocumentproperties/appversion) { get; } | 返回應用程式版本。唯讀 String。 |
| [Author](../../aspose.slides/idocumentproperties/author) { get; set; } | 返回或設定簡報的作者。讀/寫 String。 |
| [Category](../../aspose.slides/idocumentproperties/category) { get; set; } | 返回或設定簡報的類別。讀/寫 String。 |
| [Comments](../../aspose.slides/idocumentproperties/comments) { get; set; } | 返回或設定簡報的註解。讀/寫 String。 |
| [Company](../../aspose.slides/idocumentproperties/company) { get; set; } | 返回或設定公司屬性。讀/寫 String。 |
| [ContentStatus](../../aspose.slides/idocumentproperties/contentstatus) { get; set; } | 返回或設定簡報的內容狀態。讀/寫 String。 |
| [ContentType](../../aspose.slides/idocumentproperties/contenttype) { get; set; } | 返回或設定簡報的內容類型。讀/寫 String。 |
| [CountOfCustomProperties](../../aspose.slides/idocumentproperties/countofcustomproperties) { get; } | 返回集合中實際包含的自訂屬性數量。唯讀 Int32。 |
| [CreatedTime](../../aspose.slides/idocumentproperties/createdtime) { get; set; } | 返回簡報建立的日期。值採用 UTC。讀/寫 DateTime。 |
| [HeadingPairs](../../aspose.slides/idocumentproperties/headingpairs) { get; } | 指出文件部件的分組以及每個組中的部件數量。唯讀 IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/idocumentproperties/hiddenslides) { get; } | 指定簡報文件中隱藏投影片的數量。唯讀 Int32。 |
| [HyperlinkBase](../../aspose.slides/idocumentproperties/hyperlinkbase) { get; set; } | 返回或設定 HyperlinkBase 文件屬性。讀/寫 String。 |
| [HyperlinksChanged](../../aspose.slides/idocumentproperties/hyperlinkschanged) { get; set; } | 指定此部件中的一個或多個超連結已由產生者專屬於此部件更新。下一個開啟此文件的產生者應使用此部件中指定的新超連結更新超連結關係。讀/寫 Boolean。 |
| [Item](../../aspose.slides/idocumentproperties/item) { get; set; } | 返回或設定與指定名稱關聯的自訂屬性。讀/寫 Object。 |
| [Keywords](../../aspose.slides/idocumentproperties/keywords) { get; set; } | 返回或設定簡報的關鍵字。讀/寫 String。 |
| [LastPrinted](../../aspose.slides/idocumentproperties/lastprinted) { get; set; } | 返回簡報上次列印的日期。讀/寫 DateTime。 |
| [LastSavedBy](../../aspose.slides/idocumentproperties/lastsavedby) { get; set; } | 返回或設定最後修改簡報之人的名稱。讀/寫 String。 |
| [LastSavedTime](../../aspose.slides/idocumentproperties/lastsavedtime) { get; set; } | 返回簡報最後修改的日期。值採用 UTC。若為 Presentation.DocumentProperties 時為唯讀（因為在 IPresentation 物件儲存過程中會內部更新）。可透過方法 [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties) 回傳的 DocumentProperties 實例進行變更。請參閱 [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties) 方法摘要中的範例。 |
| [LinksUpToDate](../../aspose.slides/idocumentproperties/linksuptodate) { get; set; } | 指示文件中的超連結是否為最新。將此元素設為 **true** 表示超連結已更新。將此元素設為 **false** 表示超連結已過時。讀/寫 Boolean。 |
| [Manager](../../aspose.slides/idocumentproperties/manager) { get; set; } | 返回或設定管理者屬性。讀/寫 String。 |
| [MultimediaClips](../../aspose.slides/idocumentproperties/multimediaclips) { get; } | 指定文件中存在的音訊或影片剪輯總數。唯讀 Int32。 |
| [NameOfApplication](../../aspose.slides/idocumentproperties/nameofapplication) { get; set; } | 返回或設定應用程式的名稱。讀/寫 String。 |
| [Notes](../../aspose.slides/idocumentproperties/notes) { get; } | 指定含有備註的簡報投影片數量。唯讀 Int32。 |
| [Paragraphs](../../aspose.slides/idocumentproperties/paragraphs) { get; } | 指定文件中（若適用）找到的段落總數。唯讀 Int32。 |
| [PresentationFormat](../../aspose.slides/idocumentproperties/presentationformat) { get; set; } | 返回或設定簡報的預期格式。讀/寫 String。 |
| [RevisionNumber](../../aspose.slides/idocumentproperties/revisionnumber) { get; set; } | 返回或設定簡報的修訂號碼。讀/寫 Int32。 |
| [ScaleCrop](../../aspose.slides/idocumentproperties/scalecrop) { get; set; } | 指示文件縮圖的顯示模式。將此元素設為 **true** 以啟用將文件縮圖縮放至顯示區。將此元素設為 **false** 以啟用裁切文件縮圖，只顯示符合顯示區的部分。讀/寫 Boolean。 |
| [SharedDoc](../../aspose.slides/idocumentproperties/shareddoc) { get; set; } | 決定簡報是否在多位使用者之間共享。讀/寫 Boolean。 |
| [Slides](../../aspose.slides/idocumentproperties/slides) { get; } | 指定簡報文件中的投影片總數。唯讀 Int32。 |
| [Subject](../../aspose.slides/idocumentproperties/subject) { get; set; } | 返回或設定簡報的主旨。讀/寫 String。 |
| [Title](../../aspose.slides/idocumentproperties/title) { get; set; } | 返回或設定簡報的標題。讀/寫 String。 |
| [TitlesOfParts](../../aspose.slides/idocumentproperties/titlesofparts) { get; } | 指定每個文件部件的標題。這些部件不是實際的文件部件，而是文件區段的概念性表示。唯讀 string[]. |
| [TotalEditingTime](../../aspose.slides/idocumentproperties/totaleditingtime) { get; set; } | 簡報的總編輯時間。讀/寫 TimeSpan。 |
| [Words](../../aspose.slides/idocumentproperties/words) { get; } | 指定文件中包含的總字數。唯讀 Int32。 |

## 方法

| 名稱 | 說明 |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/idocumentproperties/clearbuiltinproperties)() | 清除並設定所有內建屬性的預設值。 |
| [ClearCustomProperties](../../aspose.slides/idocumentproperties/clearcustomproperties)() | 移除所有自訂屬性。 |
| [ContainsCustomProperty](../../aspose.slides/idocumentproperties/containscustomproperty)(string) | 檢查是否存在具有指定名稱的自訂屬性。 |
| [GetCustomPropertyName](../../aspose.slides/idocumentproperties/getcustompropertyname)(int) | 在指定的索引處返回自訂屬性名稱。 |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | 從自訂屬性取得具名的布林值。 |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | 從自訂屬性取得具名的 DateTime 值。 |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | 從自訂屬性取得具名的 double 值。 |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | 從自訂屬性取得具名的 float 值。 |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | 從自訂屬性取得具名的整數值。 |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | 從自訂屬性取得具名的字串值。 |
| [GetSensitivityLabels](../../aspose.slides/idocumentproperties/getsensitivitylabels)() | 從自訂文件屬性取得敏感度標籤陣列（Microsoft Information Protection SDK Metadata）。 |
| [RemoveCustomProperty](../../aspose.slides/idocumentproperties/removecustomproperty)(string) | 移除與指定名稱關聯的自訂屬性。 |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | 設定具名的布林自訂屬性。 |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | 設定具名的 DateTime 自訂屬性。 |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | 設定具名的 double 自訂屬性。 |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | 設定具名的 float 自訂屬性。 |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | 設定具名的整數自訂屬性。 |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | 設定具名的字串自訂屬性。 |

### 相關參考

* 命名空間 [Aspose.Slides](../../aspose.slides)
* 程式集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->