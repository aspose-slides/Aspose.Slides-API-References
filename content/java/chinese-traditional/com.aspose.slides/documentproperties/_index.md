---
title: DocumentProperties
second_title: Aspose.Slides for Java API 參考
description: 表示簡報的屬性。
type: docs
url: /zh-hant/com.aspose.slides/documentproperties/
---
**繼承：**
java.lang.Object

**所有已實作的介面：**
[com.aspose.slides.IDocumentProperties](../../com.aspose.slides/idocumentproperties), com.aspose.slides.IGenericCloneable, java.lang.Cloneable
```
public class DocumentProperties implements IDocumentProperties, IGenericCloneable<IDocumentProperties>, Cloneable
```

表示簡報的屬性。

--------------------

> ```
> The following example shows how to access built-in Properties of PowerPoint Presentation.
>  
>  // Instantiate the Presentation class that represents the presentation
>  Presentation pres = new Presentation("AccessBuiltin Properties.pptx");
>  try {
>      // Create a reference to IDocumentProperties object associated with Presentation
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // Display the builtin properties
>      System.out.println("Category : " + documentProperties.getCategory());
>      System.out.println("Current Status : " + documentProperties.getContentStatus());
>      System.out.println("Creation Date : " + documentProperties.getCreatedTime());
>      System.out.println("Author : " + documentProperties.getAuthor());
>      System.out.println("Description : " + documentProperties.getComments());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to modify built-in Properties of PowerPoint Presentation.
>  
>  // Instantiate the Presentation class that represents the Presentation
>  Presentation pres = new Presentation("ModifyBuiltinProperties.pptx");
>  try {
>      // Create a reference to IDocumentProperties object associated with Presentation
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // Set the builtin properties
>      documentProperties.setAuthor("Aspose.Slides for Java");
>      documentProperties.setTitle("Modifying Presentation Properties");
>      documentProperties.setSubject("Aspose Subject");
>      // Save your presentation to a file
>      pres.save("DocumentProperties_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## 建構子

| 建構函式 | 說明 |
| --- | --- |
| [DocumentProperties()](#DocumentProperties--) | 初始化 [DocumentProperties](../../com.aspose.slides/documentproperties) 類別的新實例。 |
## 方法

| 方法 | 說明 |
| --- | --- |
| [getAppVersion()](#getAppVersion--) | 傳回應用程式版本。 |
| [getNameOfApplication()](#getNameOfApplication--) | 傳回或設定應用程式的名稱。 |
| [setNameOfApplication(String value)](#setNameOfApplication-java.lang.String-) | 傳回或設定應用程式的名稱。 |
| [getCompany()](#getCompany--) | 傳回或設定公司屬性。 |
| [setCompany(String value)](#setCompany-java.lang.String-) | 傳回或設定公司屬性。 |
| [getManager()](#getManager--) | 傳回或設定管理者屬性。 |
| [setManager(String value)](#setManager-java.lang.String-) | 傳回或設定管理者屬性。 |
| [getPresentationFormat()](#getPresentationFormat--) | 傳回或設定簡報的預期格式。 |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | 傳回或設定簡報的預期格式。 |
| [getSharedDoc()](#getSharedDoc--) | 判斷簡報是否與多個人共用。 |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | 判斷簡報是否與多個人共用。 |
| [getApplicationTemplate()](#getApplicationTemplate--) | 傳回或設定應用程式的範本。 |
| [setApplicationTemplate(String value)](#setApplicationTemplate-java.lang.String-) | 傳回或設定應用程式的範本。 |
| [getTotalEditingTime()](#getTotalEditingTime--) | 簡報的總編輯時間。 |
| [setTotalEditingTime(double value)](#setTotalEditingTime-double-) | 簡報的總編輯時間。 |
| [getTitle()](#getTitle--) | 傳回或設定簡報的標題。 |
| [setTitle(String value)](#setTitle-java.lang.String-) | 傳回或設定簡報的標題。 |
| [getSubject()](#getSubject--) | 傳回或設定簡報的主旨。 |
| [setSubject(String value)](#setSubject-java.lang.String-) | 傳回或設定簡報的主旨。 |
| [getAuthor()](#getAuthor--) | 傳回或設定簡報的作者。 |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | 傳回或設定簡報的作者。 |
| [getKeywords()](#getKeywords--) | 傳回或設定簡報的關鍵字。 |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | 傳回或設定簡報的關鍵字。 |
| [getComments()](#getComments--) | 傳回或設定簡報的註解。 |
| [setComments(String value)](#setComments-java.lang.String-) | 傳回或設定簡報的註解。 |
| [getCategory()](#getCategory--) | 傳回或設定簡報的類別。 |
| [setCategory(String value)](#setCategory-java.lang.String-) | 傳回或設定簡報的類別。 |
| [getCreatedTime()](#getCreatedTime--) | 傳回簡報建立的日期。 |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | 傳回簡報建立的日期。 |
| [getLastSavedTime()](#getLastSavedTime--) | 傳回簡報最後修改的日期。 |
| [setLastSavedTime(Date value)](#setLastSavedTime-java.util.Date-) | 傳回簡報最後修改的日期。 |
| [getLastPrinted()](#getLastPrinted--) | 傳回簡報最後一次列印的日期。 |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | 傳回簡報最後一次列印的日期。 |
| [getLastSavedBy()](#getLastSavedBy--) | 傳回或設定最後修改簡報之使用者名稱。 |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | 傳回或設定最後修改簡報之使用者名稱。 |
| [getRevisionNumber()](#getRevisionNumber--) | 傳回或設定簡報的版本號。 |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | 傳回或設定簡報的版本號。 |
| [getContentStatus()](#getContentStatus--) | 傳回或設定簡報的內容狀態。 |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | 傳回或設定簡報的內容狀態。 |
| [getContentType()](#getContentType--) | 傳回或設定簡報的內容類型。 |
| [setContentType(String value)](#setContentType-java.lang.String-) | 傳回或設定簡報的內容類型。 |
| [getHyperlinkBase()](#getHyperlinkBase--) | 傳回或設定 HyperlinkBase 文件屬性。 |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | 傳回或設定 HyperlinkBase 文件屬性。 |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | 傳回集合中實際包含的自訂屬性數量。 |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | 傳回指定索引處的自訂屬性名稱。 |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | 移除與指定名稱關聯的自訂屬性。 |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | 檢查是否存在具有指定名稱的自訂屬性。 |
| [get_Item(String name)](#get-Item-java.lang.String-) | 傳回或設定與指定名稱關聯的自訂屬性。 |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | 傳回或設定與指定名稱關聯的自訂屬性。 |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | 從自訂屬性取得具名的布林值。 |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | 從自訂屬性取得具名的整數值。 |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | 從自訂屬性取得具名的日期時間值。 |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | 從自訂屬性取得具名的字串值。 |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | 從自訂屬性取得具名的浮點數值。 |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | 從自訂屬性取得具名的雙精度浮點數值。 |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | 設定具名的布林自訂屬性。 |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | 設定具名的整數自訂屬性。 |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | 設定具名的日期時間自訂屬性。 |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | 設定具名的字串自訂屬性。 |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | 設定具名的浮點數自訂屬性。 |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | 設定具名的雙精度浮點數自訂屬性。 |
| [clearCustomProperties()](#clearCustomProperties--) | 移除所有自訂屬性。 |
| [getSensitivityLabels()](#getSensitivityLabels--) | 取得自訂文件屬性中的敏感度標籤陣列（Microsoft Information Protection SDK Metadata）。 |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | 清除並設定所有內建屬性的預設值。 |
| [getScaleCrop()](#getScaleCrop--) | 指示文件縮圖的顯示模式。 |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | 指示文件縮圖的顯示模式。 |
| [getLinksUpToDate()](#getLinksUpToDate--) | 指示文件中的超連結是否為最新狀態。 |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | 指示文件中的超連結是否為最新狀態。 |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | 指定此部份中的一或多個超連結僅由產生者在此部份更新。 |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | 指定此部份中的一或多個超連結僅由產生者在此部份更新。 |
| [getSlides()](#getSlides--) | 傳回簡報文件中的投影片總數。 |
| [getHiddenSlides()](#getHiddenSlides--) | 傳回簡報文件中隱藏的投影片數量。 |
| [getNotes()](#getNotes--) | 傳回含有備註的投影片數量。 |
| [getParagraphs()](#getParagraphs--) | 傳回文件中找到的段落總數（如適用）。 |
| [getWords()](#getWords--) | 傳回文件中包含的字數總計。 |
| [getMultimediaClips()](#getMultimediaClips--) | 傳回文件中存在的音訊或影片剪輯總數。 |
| [getTitlesOfParts()](#getTitlesOfParts--) | 指定每個文件部份的標題。 |
| [getHeadingPairs()](#getHeadingPairs--) | 指示文件部份的分組以及每組的部份數量。 |
| [deepClone()](#deepClone--) | 複製目前的物件 |
| [cloneT()](#cloneT--) | 複製目前的物件 |
### DocumentProperties() {#DocumentProperties--}
```
public DocumentProperties()
```

初始化 [DocumentProperties](../../com.aspose.slides/documentproperties) 類別的新實例。

### getAppVersion() {#getAppVersion--}
```
public final String getAppVersion()
```

傳回應用程式版本。唯讀字串。

**傳回：**
java.lang.String
### getNameOfApplication() {#getNameOfApplication--}
```
public final String getNameOfApplication()
```

傳回或設定應用程式的名稱。讀寫字串。

**傳回：**
java.lang.String
### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public final void setNameOfApplication(String value)
```

傳回或設定應用程式的名稱。讀寫字串。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getCompany() {#getCompany--}
```
public final String getCompany()
```

傳回或設定公司屬性。讀寫字串。

**傳回：**
java.lang.String
### setCompany(String value) {#setCompany-java.lang.String-}
```
public final void setCompany(String value)
```

傳回或設定公司屬性。讀寫字串。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getManager() {#getManager--}
```
public final String getManager()
```

傳回或設定管理者屬性。讀寫字串。

**傳回：**
java.lang.String
### setManager(String value) {#setManager-java.lang.String-}
```
public final void setManager(String value)
```

傳回或設定管理者屬性。讀寫字串。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getPresentationFormat() {#getPresentationFormat--}
```
public final String getPresentationFormat()
```

傳回或設定簡報的預期格式。讀寫字串。

**傳回：**
java.lang.String
### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public final void setPresentationFormat(String value)
```

傳回或設定簡報的預期格式。讀寫字串。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getSharedDoc() {#getSharedDoc--}
```
public final boolean getSharedDoc()
```

判斷簡報是否與多個人共用。讀寫布林。

**傳回：**
boolean
### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public final void setSharedDoc(boolean value)
```

判斷簡報是否與多個人共用。讀寫布林。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getApplicationTemplate() {#getApplicationTemplate--}
```
public final String getApplicationTemplate()
```

傳回或設定應用程式的範本。讀寫字串。

**傳回：**
java.lang.String
### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public final void setApplicationTemplate(String value)
```

傳回或設定應用程式的範本。讀寫字串。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getTotalEditingTime() {#getTotalEditingTime--}
```
public final double getTotalEditingTime()
```

簡報的總編輯時間。讀寫 double。

**傳回：**
double
### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public final void setTotalEditingTime(double value)
```

簡報的總編輯時間。讀寫 double。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |

### getTitle() {#getTitle--}
```
public final String getTitle()
```

傳回或設定簡報的標題。讀寫字串。

**傳回：**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```

傳回或設定簡報的標題。讀寫字串。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```

傳回或設定簡報的主旨。讀寫字串。

**傳回：**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```

傳回或設定簡報的主旨。讀寫字串。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getAuthor() {#getAuthor--}
```
public final String getAuthor()
```

傳回或設定簡報的作者。讀寫字串。

**傳回：**
java.lang.String
### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public final void setAuthor(String value)
```

傳回或設定簡報的作者。讀寫字串。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getKeywords() {#getKeywords--}
```
public final String getKeywords()
```

傳回或設定簡報的關鍵字。讀寫字串。

**傳回：**
java.lang.String
### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public final void setKeywords(String value)
```

傳回或設定簡報的關鍵字。讀寫字串。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public final String getComments()
```

傳回或設定簡報的註解。讀寫字串。

**傳回：**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```

傳回或設定簡報的註解。讀寫字串。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getCategory() {#getCategory--}
```
public final String getCategory()
```

傳回或設定簡報的類別。讀寫字串。

**傳回：**
java.lang.String
### setCategory(String value) {#setCategory-java.lang.String-}
```
public final void setCategory(String value)
```

傳回或設定簡報的類別。讀寫字串。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```
返回簡報建立的日期。值以 UTC 表示。可讀寫 java.util.Date。

**返回：**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```

返回簡報建立的日期。值以 UTC 表示。可讀寫 java.util.Date。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedTime() {#getLastSavedTime--}
```
public final Date getLastSavedTime()
```

返回簡報最後一次修改的日期。值以 UTC 表示。對於 Presentation.DocumentProperties 為唯讀（因為在 IPresentation 物件保存過程中會內部更新）。可透過方法 [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) 回傳的 DocumentProperties 實例變更。請參考 [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-) 方法摘要中的範例。

**返回：**
java.util.Date
### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public final void setLastSavedTime(Date value)
```

返回簡報最後一次修改的日期。值以 UTC 表示。對於 Presentation.DocumentProperties 為唯讀（因為在 IPresentation 物件保存過程中會內部更新）。可透過方法 [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) 回傳的 DocumentProperties 實例變更。請參考 [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-) 方法摘要中的範例。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastPrinted() {#getLastPrinted--}
```
public final Date getLastPrinted()
```

返回簡報最後一次列印的日期。可讀寫 java.util.Date。

**返回：**
java.util.Date
### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public final void setLastPrinted(Date value)
```

返回簡報最後一次列印的日期。可讀寫 java.util.Date。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedBy() {#getLastSavedBy--}
```
public final String getLastSavedBy()
```

返回或設定最後一次修改簡報的使用者名稱。可讀寫 String。

**返回：**
java.lang.String
### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public final void setLastSavedBy(String value)
```

返回或設定最後一次修改簡報的使用者名稱。可讀寫 String。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getRevisionNumber() {#getRevisionNumber--}
```
public final int getRevisionNumber()
```

返回或設定簡報的修訂號碼。可讀寫 int。

**返回：**
int
### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public final void setRevisionNumber(int value)
```

返回或設定簡報的修訂號碼。可讀寫 int。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getContentStatus() {#getContentStatus--}
```
public final String getContentStatus()
```

返回或設定簡報的內容狀態。可讀寫 String。

**返回：**
java.lang.String
### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public final void setContentStatus(String value)
```

返回或設定簡報的內容狀態。可讀寫 String。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getContentType() {#getContentType--}
```
public final String getContentType()
```

返回或設定簡報的內容類型。可讀寫 String。

**返回：**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```

返回或設定簡報的內容類型。可讀寫 String。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getHyperlinkBase() {#getHyperlinkBase--}
```
public final String getHyperlinkBase()
```

返回或設定 HyperlinkBase 文件屬性。可讀寫 String。

**返回：**
java.lang.String
### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public final void setHyperlinkBase(String value)
```

返回或設定 HyperlinkBase 文件屬性。可讀寫 String。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public final int getCountOfCustomProperties()
```

返回集合中實際包含的自訂屬性數量。唯讀 int。

**返回：**
int
### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public final String getCustomPropertyName(int index)
```

返回指定索引處的自訂屬性名稱。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要取得的自訂屬性的零基索引。 |

**返回：**
java.lang.String - 指定索引處的自訂屬性名稱。
### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public final boolean removeCustomProperty(String name)
```

移除具有指定名稱的自訂屬性。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 要移除的自訂屬性名稱。 |

**返回：**
boolean - 若屬性被移除則回傳 true，否則回傳 false。
### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public final boolean containsCustomProperty(String name)
```

檢查是否存在具有指定名稱的自訂屬性。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 要檢查的自訂屬性名稱。 |

**返回：**
boolean - 若屬性存在則回傳 true，否則回傳 false。
### get_Item(String name) {#get-Item-java.lang.String-}
```
public final Object get_Item(String name)
```

返回或設定具有指定名稱的自訂屬性。可讀寫 Object。

--------------------

值可以是 **int**、**float**、**String**、**boolean** 或 **Date**。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String |  |

**返回：**
java.lang.Object
### set_Item(String name, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public final void set_Item(String name, Object value)
```

返回或設定具有指定名稱的自訂屬性。可讀寫 Object。

--------------------

值可以是 **int**、**float**、**String**、**boolean** 或 **Date**。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String |  |
| value | java.lang.Object |  |
### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public final void getCustomPropertyValue(String name, boolean[] value)
```

從自訂屬性中取得指定名稱的布林值。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 要取得的自訂屬性名稱 |
| value | boolean[] | 自訂屬性值 |
### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public final void getCustomPropertyValue(String name, int[] value)
```

從自訂屬性中取得指定名稱的整數值。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 要取得的自訂屬性名稱 |
| value | int[] | 自訂屬性值 |
### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public final void getCustomPropertyValue(String name, Date[] value)
```

從自訂屬性中取得指定名稱的 DateTime 值。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 要取得的自訂屬性名稱 |
| value | java.util.Date[] | 自訂屬性值 |
### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public final void getCustomPropertyValue(String name, String[] value)
```

從自訂屬性中取得指定名稱的字串值。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 要取得的自訂屬性名稱 |
| value | java.lang.String[] | 自訂屬性值 |
### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public final void getCustomPropertyValue(String name, float[] value)
```

從自訂屬性中取得指定名稱的浮點值。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 要取得的自訂屬性名稱 |
| value | float[] | 自訂屬性值 |
### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public final void getCustomPropertyValue(String name, double[] value)
```

從自訂屬性中取得指定名稱的雙精度值。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 要取得的自訂屬性名稱。 |
| value | double[] | 自訂屬性值 |
### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public final void setCustomPropertyValue(String name, boolean value)
```

設定指定名稱的布林自訂屬性。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 要設定的自訂屬性名稱 |
| value | boolean | 自訂屬性值 |
### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public final void setCustomPropertyValue(String name, int value)
```

設定指定名稱的整數自訂屬性。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 要設定的自訂屬性名稱 |
| value | int | 自訂屬性值 |
### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public final void setCustomPropertyValue(String name, Date value)
```

設定指定名稱的 DateTime 自訂屬性。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 要設定的自訂屬性名稱 |
| value | java.util.Date | 自訂屬性值 |
### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public final void setCustomPropertyValue(String name, String value)
```

設定指定名稱的字串自訂屬性。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 要設定的自訂屬性名稱 |
| value | java.lang.String | 自訂屬性值 |
### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public final void setCustomPropertyValue(String name, float value)
```

設定指定名稱的浮點自訂屬性。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 要設定的自訂屬性名稱 |
| value | float | 自訂屬性值 |
### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public final void setCustomPropertyValue(String name, double value)
```

設定指定名稱的雙精度自訂屬性。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 要設定的自訂屬性名稱 |
| value | double | 自訂屬性值 |
### clearCustomProperties() {#clearCustomProperties--}
```
public final void clearCustomProperties()
```

移除所有自訂屬性。

### getSensitivityLabels() {#getSensitivityLabels--}
```
public final ISensitivityLabel[] getSensitivityLabels()
```

取得自訂文件屬性中的敏感度標籤陣列（Microsoft Information Protection SDK Metadata）。

--------------------

> ```
> The following code shows how to move the sensitivity labels information from the custom document properties 
>   to the modern SensitivityLabels collection:
>   
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // Get sensitivity labels from the custom document properties
>      ISensitivityLabel[] mipSensitivityLabels = pres.getDocumentProperties().getSensitivityLabels();
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
>      for (ISensitivityLabel sensitivityLabel : mipSensitivityLabels)
>      {
>          // Add label to the collection
>          // Here you can add a check for the validity of the label information (the label is available, etc)
>          sensitivityLabels.add(sensitivityLabel);
>      }
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回：**
com.aspose.slides.ISensitivityLabel[]
### clearBuiltInProperties() {#clearBuiltInProperties--}
```
public final void clearBuiltInProperties()
```

清除並將所有內建屬性設定為預設值。

### getScaleCrop() {#getScaleCrop--}
```
public final boolean getScaleCrop()
```

指示文件縮圖的顯示模式。將此元素設為 **true** 可啟用縮圖縮放以符合顯示區域。將此元素設為 **false** 可啟用裁切，只顯示適合顯示區域的部分。可讀寫 boolean。

**返回：**
boolean
### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public final void setScaleCrop(boolean value)
```

指示文件縮圖的顯示模式。將此元素設為 **true** 可啟用縮圖縮放以符合顯示區域。將此元素設為 **false** 可啟用裁切，只顯示適合顯示區域的部分。可讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getLinksUpToDate() {#getLinksUpToDate--}
```
public final boolean getLinksUpToDate()
```

指示文件中的超連結是否為最新。將此元素設為 **true** 表示超連結已更新。將此元素設為 **false** 表示超連結已過期。可讀寫 boolean。

**返回：**
boolean
### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public final void setLinksUpToDate(boolean value)
```
指示文件中的超連結是否為最新。將此元素設為 **true** 以表示超連結已更新。將此元素設為 **false** 以表示超連結已過時。讀寫 boolean。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public final boolean getHyperlinksChanged()
```

指定此部分中的一個或多個超連結僅由製作者在此部分更新。下一個開啟此文件的製作者應使用此部分中指定的新超連結更新超連結關係。讀寫 boolean。

**返回:**  
boolean
### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public final void setHyperlinksChanged(boolean value)
```

指定此部分中的一個或多個超連結僅由製作者在此部分更新。下一個開啟此文件的製作者應使用此部分中指定的新超連結更新超連結關係。讀寫 boolean。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getSlides() {#getSlides--}
```
public final int getSlides()
```

返回簡報文件中投影片的總數。唯讀 int。

**返回:**  
int
### getHiddenSlides() {#getHiddenSlides--}
```
public final int getHiddenSlides()
```

返回簡報文件中隱藏投影片的數量。唯讀 int。

**返回:**  
int
### getNotes() {#getNotes--}
```
public final int getNotes()
```

返回包含註釋的簡報投影片數量。唯讀 int。

**返回:**  
int
### getParagraphs() {#getParagraphs--}
```
public final int getParagraphs()
```

返回文件中找到的段落總數（若適用）。唯讀 int。

**返回:**  
int
### getWords() {#getWords--}
```
public final int getWords()
```

返回文件中包含的單詞總數。唯讀 int。

**返回:**  
int
### getMultimediaClips() {#getMultimediaClips--}
```
public final int getMultimediaClips()
```

返回文件中存在的聲音或影片剪輯的總數。唯讀 int。

**返回:**  
int
### getTitlesOfParts() {#getTitlesOfParts--}
```
public final String[] getTitlesOfParts()
```

指定每個文件部分的標題。這些部分不是文件部分，而是文件節的概念性表示。唯讀 String[]。

**返回:**  
java.lang.String[]
### getHeadingPairs() {#getHeadingPairs--}
```
public final IHeadingPair[] getHeadingPairs()
```

指示文件部分的分組以及每個組中的部分數量。唯讀 IHeadingPair[]。

**返回:**  
com.aspose.slides.IHeadingPair[]
### deepClone() {#deepClone--}
```
public final Object deepClone()
```

複製目前的物件

**返回:**  
java.lang.Object - Clone
### cloneT() {#cloneT--}
```
public final IDocumentProperties cloneT()
```

複製目前的物件

**返回:**  
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - Clone