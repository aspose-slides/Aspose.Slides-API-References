---
title: DocumentProperties
second_title: Aspose.Sildes for .NET API 參考文件
description: 表示簡報的屬性。
type: docs
weight: 2810
url: /zh-hant/aspose.slides/documentproperties/
---
## DocumentProperties 類別

表示簡報的屬性。

```csharp
public class DocumentProperties : IDocumentProperties, IGenericCloneable<IDocumentProperties>
```

## 建構函式

| Name | Description |
| --- | --- |
| [DocumentProperties](documentproperties)() | 初始化 [`DocumentProperties`](../documentproperties) 類別的新執行個體。 |

## 屬性

| Name | Description |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/documentproperties/applicationtemplate) { get; set; } | 傳回或設定應用程式的範本。讀寫 String。 |
| [AppVersion](../../aspose.slides/documentproperties/appversion) { get; } | 傳回應用程式版本。唯讀 String。 |
| [Author](../../aspose.slides/documentproperties/author) { get; set; } | 傳回或設定簡報的作者。讀寫 String。 |
| [Category](../../aspose.slides/documentproperties/category) { get; set; } | 傳回或設定簡報的類別。讀寫 String。 |
| [Comments](../../aspose.slides/documentproperties/comments) { get; set; } | 傳回或設定簡報的註解。讀寫 String。 |
| [Company](../../aspose.slides/documentproperties/company) { get; set; } | 傳回或設定公司屬性。讀寫 String。 |
| [ContentStatus](../../aspose.slides/documentproperties/contentstatus) { get; set; } | 傳回或設定簡報的內容狀態。讀寫 String。 |
| [ContentType](../../aspose.slides/documentproperties/contenttype) { get; set; } | 傳回或設定簡報的內容類型。讀寫 String。 |
| [CountOfCustomProperties](../../aspose.slides/documentproperties/countofcustomproperties) { get; } | 傳回集合中實際包含的自訂屬性數量。唯讀 Int32。 |
| [CreatedTime](../../aspose.slides/documentproperties/createdtime) { get; set; } | 傳回簡報建立的日期。值為 UTC 時間。讀寫 DateTime。 |
| [HeadingPairs](../../aspose.slides/documentproperties/headingpairs) { get; } | 指出文件部分的分組以及每個群組中的部分數量。唯讀 IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/documentproperties/hiddenslides) { get; } | 傳回簡報文件中隱藏投影片的數量。唯讀 Int32。 |
| [HyperlinkBase](../../aspose.slides/documentproperties/hyperlinkbase) { get; set; } | 傳回或設定 HyperlinkBase 文件屬性。讀寫 String。 |
| [HyperlinksChanged](../../aspose.slides/documentproperties/hyperlinkschanged) { get; set; } | 指定此部分中的一個或多個超連結僅由產作者在此部分更新。下一個開啟此文件的產作者應使用此部分中指定的新超連結更新超連結關係。讀寫 Boolean。 |
| [Item](../../aspose.slides/documentproperties/item) { get; set; } | 傳回或設定與指定名稱相關聯的自訂屬性。讀寫 Object。 |
| [Keywords](../../aspose.slides/documentproperties/keywords) { get; set; } | 傳回或設定簡報的關鍵字。讀寫 String。 |
| [LastPrinted](../../aspose.slides/documentproperties/lastprinted) { get; set; } | 傳回簡報最後一次列印的日期。讀寫 DateTime。 |
| [LastSavedBy](../../aspose.slides/documentproperties/lastsavedby) { get; set; } | 傳回或設定最後修改簡報的人的名稱。讀寫 String。 |
| [LastSavedTime](../../aspose.slides/documentproperties/lastsavedtime) { get; set; } | 傳回簡報最後一次修改的日期。值為 UTC。對於 Presentation.DocumentProperties 為唯讀（因為在 IPresentation 物件儲存過程中會在內部更新）。可以透過方法 [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties) 回傳的 DocumentProperties 實例進行變更。請參閱 [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties) 方法摘要中的範例。 |
| [LinksUpToDate](../../aspose.slides/documentproperties/linksuptodate) { get; set; } | 指出文件中的超連結是否為最新。將此元素設為 **true** 表示超連結已更新。將此元素設為 **false** 表示超連結已過時。讀寫 Boolean。 |
| [Manager](../../aspose.slides/documentproperties/manager) { get; set; } | 傳回或設定管理員屬性。讀寫 String。 |
| [MultimediaClips](../../aspose.slides/documentproperties/multimediaclips) { get; } | 傳回文件中存在的音訊或視訊剪輯總數。唯讀 Int32。 |
| [NameOfApplication](../../aspose.slides/documentproperties/nameofapplication) { get; set; } | 傳回或設定應用程式的名稱。讀寫 String。 |
| [Notes](../../aspose.slides/documentproperties/notes) { get; } | 傳回簡報中包含備註的投影片數量。唯讀 Int32。 |
| [Paragraphs](../../aspose.slides/documentproperties/paragraphs) { get; } | 傳回文件中找到的段落總數（如適用）。唯讀 Int32。 |
| [PresentationFormat](../../aspose.slides/documentproperties/presentationformat) { get; set; } | 傳回或設定簡報的預期格式。讀寫 String。 |
| [RevisionNumber](../../aspose.slides/documentproperties/revisionnumber) { get; set; } | 傳回或設定簡報的修訂號碼。讀寫 Int32。 |
| [ScaleCrop](../../aspose.slides/documentproperties/scalecrop) { get; set; } | 指出文件縮圖的顯示模式。將此元素設為 **true** 以啟用將文件縮圖縮放至顯示區。將此元素設為 **false** 以啟用裁切文件縮圖，只顯示符合顯示區的部分。讀寫 Boolean。 |
| [SharedDoc](../../aspose.slides/documentproperties/shareddoc) { get; set; } | 決定簡報是否在多個使用者之間分享。讀寫 Boolean。 |
| [Slides](../../aspose.slides/documentproperties/slides) { get; } | 傳回簡報文件中投影片的總數。唯讀 Int32。 |
| [Subject](../../aspose.slides/documentproperties/subject) { get; set; } | 傳回或設定簡報的主旨。讀寫 String。 |
| [Title](../../aspose.slides/documentproperties/title) { get; set; } | 傳回或設定簡報的標題。讀寫 String。 |
| [TitlesOfParts](../../aspose.slides/documentproperties/titlesofparts) { get; } | 指定每個文件部分的標題。這些部分不是實際文件部分，而是文件章節的概念性表示。唯讀 string[]. |
| [TotalEditingTime](../../aspose.slides/documentproperties/totaleditingtime) { get; set; } | 簡報的總編輯時間。讀寫 TimeSpan。 |
| [Words](../../aspose.slides/documentproperties/words) { get; } | 傳回文件中包含的總字數。唯讀 Int32。 |

## 方法

| Name | Description |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/documentproperties/clearbuiltinproperties)() | 清除並為所有內建屬性設定預設值。 |
| [ClearCustomProperties](../../aspose.slides/documentproperties/clearcustomproperties)() | 移除所有自訂屬性。 |
| [Clone](../../aspose.slides/documentproperties/clone)() | 複製目前物件 |
| [CloneT](../../aspose.slides/documentproperties/clonet)() | 複製目前物件 |
| [ContainsCustomProperty](../../aspose.slides/documentproperties/containscustomproperty)(string) | 檢查具有指定名稱的自訂屬性是否存在。 |
| [GetCustomPropertyName](../../aspose.slides/documentproperties/getcustompropertyname)(int) | 在指定索引處傳回自訂屬性名稱。 |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | 從自訂屬性取得具名的布林值。 |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | 從自訂屬性取得具名的 DateTime 值。 |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | 從自訂屬性取得具名的 double 值。 |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | 從自訂屬性取得具名的 float 值。 |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | 從自訂屬性取得具名的整數值。 |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | 從自訂屬性取得具名的 string 值。 |
| [GetSensitivityLabels](../../aspose.slides/documentproperties/getsensitivitylabels)() | 從自訂文件屬性取得敏感度標籤陣列（Microsoft Information Protection SDK 中繼資料）。 |
| [RemoveCustomProperty](../../aspose.slides/documentproperties/removecustomproperty)(string) | 移除與指定名稱相關聯的自訂屬性。 |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | 設定具名的布林自訂屬性。 |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | 設定具名的 DateTime 自訂屬性。 |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | 設定具名的 double 自訂屬性。 |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | 設定具名的 float 自訂屬性。 |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | 設定具名的整數自訂屬性。 |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | 設定具名的 string 自訂屬性。 |

### 範例

以下範例示範如何存取 PowerPoint 簡報的內建屬性。

```csharp
[C#]
// 實例化代表簡報的 Presentation 類別
using (Presentation pres = new Presentation(dataDir + "AccessBuiltin Properties.pptx"))
{
	// 建立與 Presentation 相關聯的 IDocumentProperties 物件參考
	IDocumentProperties documentProperties = pres.DocumentProperties;
	// 顯示內建屬性
	Console.WriteLine("Category : " + documentProperties.Category);
	Console.WriteLine("Current Status : " + documentProperties.ContentStatus);
	Console.WriteLine("Creation Date : " + documentProperties.CreatedTime);
	Console.WriteLine("Author : " + documentProperties.Author);
	Console.WriteLine("Description : " + documentProperties.Comments);
}
```

以下範例示範如何修改 PowerPoint 簡報的內建屬性。

```csharp
[C#]
// 實例化代表簡報的 Presentation 類別
using (Presentation presentation = new Presentation(dataDir + "ModifyBuiltinProperties.pptx"))
{
	// 建立與 Presentation 關聯的 IDocumentProperties 物件參考
	IDocumentProperties documentProperties = presentation.DocumentProperties;
	// 設定內建屬性
	documentProperties.Author = "Aspose.Slides for .NET";
	documentProperties.Title = "Modifying Presentation Properties";
	documentProperties.Subject = "Aspose Subject";
	// 將簡報儲存至檔案
	presentation.Save(dataDir + "DocumentProperties_out.pptx", SaveFormat.Pptx);
}
```

### 參見

* 介面 [IDocumentProperties](../idocumentproperties)
* 介面 [IGenericCloneable&lt;T&gt;](../igenericcloneable-1)
* 命名空間 [Aspose.Slides](../../aspose.slides)
* 組件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->