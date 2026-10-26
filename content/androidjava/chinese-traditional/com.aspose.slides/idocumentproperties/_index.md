---
title: IDocumentProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Represents properties of a presentation.
type: docs
url: /zh-hant/com.aspose.slides/idocumentproperties/
---``` 
public interface IDocumentProperties 
```

表示簡報的屬性。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getAppVersion()](#getAppVersion--) | 返回應用程式版本。 |
| [getNameOfApplication()](#getNameOfApplication--) | 返回或設定應用程式的名稱。 |
| [setNameOfApplication(String value)](#setNameOfApplication-java.lang.String-) | 返回或設定應用程式的名稱。 |
| [getCompany()](#getCompany--) | 返回或設定公司屬性。 |
| [setCompany(String value)](#setCompany-java.lang.String-) | 返回或設定公司屬性。 |
| [getManager()](#getManager--) | 返回或設定管理者屬性。 |
| [setManager(String value)](#setManager-java.lang.String-) | 返回或設定管理者屬性。 |
| [getPresentationFormat()](#getPresentationFormat--) | 返回或設定簡報的目標格式。 |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | 返回或設定簡報的目標格式。 |
| [getSharedDoc()](#getSharedDoc--) | 判斷簡報是否在多位使用者之間共用。 |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | 判斷簡報是否在多位使用者之間共用。 |
| [getApplicationTemplate()](#getApplicationTemplate--) | 返回或設定應用程式的範本。 |
| [setApplicationTemplate(String value)](#setApplicationTemplate-java.lang.String-) | 返回或設定應用程式的範本。 |
| [getTotalEditingTime()](#getTotalEditingTime--) | 簡報的總編輯時間。 |
| [setTotalEditingTime(double value)](#setTotalEditingTime-double-) | 簡報的總編輯時間。 |
| [getTitle()](#getTitle--) | 返回或設定簡報的標題。 |
| [setTitle(String value)](#setTitle-java.lang.String-) | 返回或設定簡報的標題。 |
| [getSubject()](#getSubject--) | 返回或設定簡報的主題。 |
| [setSubject(String value)](#setSubject-java.lang.String-) | 返回或設定簡報的主題。 |
| [getAuthor()](#getAuthor--) | 返回或設定簡報的作者。 |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | 返回或設定簡報的作者。 |
| [getKeywords()](#getKeywords--) | 返回或設定簡報的關鍵字。 |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | 返回或設定簡報的關鍵字。 |
| [getComments()](#getComments--) | 返回或設定簡報的註解。 |
| [setComments(String value)](#setComments-java.lang.String-) | 返回或設定簡報的註解。 |
| [getCategory()](#getCategory--) | 返回或設定簡報的類別。 |
| [setCategory(String value)](#setCategory-java.lang.String-) | 返回或設定簡報的類別。 |
| [getCreatedTime()](#getCreatedTime--) | 返回簡報建立的日期。 |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | 返回簡報建立的日期。 |
| [getLastSavedTime()](#getLastSavedTime--) | 返回簡報最後修改的日期。 |
| [setLastSavedTime(Date value)](#setLastSavedTime-java.util.Date-) | 返回簡報最後修改的日期。 |
| [getLastPrinted()](#getLastPrinted--) | 返回簡報最後一次列印的日期。 |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | 返回簡報最後一次列印的日期。 |
| [getLastSavedBy()](#getLastSavedBy--) | 返回或設定最後修改簡報之人的名稱。 |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | 返回或設定最後修改簡報之人的名稱。 |
| [getRevisionNumber()](#getRevisionNumber--) | 返回或設定簡報的修訂號碼。 |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | 返回或設定簡報的修訂號碼。 |
| [getContentStatus()](#getContentStatus--) | 返回或設定簡報的內容狀態。 |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | 返回或設定簡報的內容狀態。 |
| [getContentType()](#getContentType--) | 返回或設定簡報的內容類型。 |
| [setContentType(String value)](#setContentType-java.lang.String-) | 返回或設定簡報的內容類型。 |
| [getHyperlinkBase()](#getHyperlinkBase--) | 返回或設定 HyperlinkBase 文件屬性。 |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | 返回或設定 HyperlinkBase 文件屬性。 |
| [getScaleCrop()](#getScaleCrop--) | 指示文件縮圖的顯示模式。 |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | 指示文件縮圖的顯示模式。 |
| [getLinksUpToDate()](#getLinksUpToDate--) | 指示文件中的超連結是否為最新。 |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | 指示文件中的超連結是否為最新。 |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | 指定此部分中的一個或多個超連結已由產生者僅在此部分更新。 |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | 指定此部分中的一個或多個超連結已由產生者僅在此部分更新。 |
| [getSlides()](#getSlides--) | 指定簡報文件中投影片的總數。 |
| [getHiddenSlides()](#getHiddenSlides--) | 指定簡報文件中隱藏投影片的數量。 |
| [getNotes()](#getNotes--) | 指定簡報中包含備註的投影片數量。 |
| [getParagraphs()](#getParagraphs--) | 指定文件中找到的段落總數（如適用）。 |
| [getWords()](#getWords--) | 指定文件中包含的單詞總數。 |
| [getMultimediaClips()](#getMultimediaClips--) | 指定文件中存在的音訊或影片剪輯的總數。 |
| [getTitlesOfParts()](#getTitlesOfParts--) | 指定每個文件部分的標題。 |
| [getHeadingPairs()](#getHeadingPairs--) | 指示文件部分的分組以及每組的部分數量。 |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | 返回集合中實際包含的自訂屬性數量。 |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | 返回指定索引處的自訂屬性名稱。 |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | 移除與指定名稱相關聯的自訂屬性。 |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | 檢查是否存在指定名稱的自訂屬性。 |
| [get_Item(String name)](#get-Item-java.lang.String-) | 返回或設定與指定名稱相關聯的自訂屬性。 |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | 返回或設定與指定名稱相關聯的自訂屬性。 |
| [clearCustomProperties()](#clearCustomProperties--) | 移除所有自訂屬性。 |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | 清除並設定所有內建屬性的預設值。 |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | Gets a named boolean value from the custom properties. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | Gets a named integer value from the custom properties. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | Gets a named DateTime value from the custom properties. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | Gets a named string value from the custom properties. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | Gets a named float value from the custom properties. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | Gets a named double value from the custom properties. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | 設定具名的布林自訂屬性。 |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | 設定具名的整數自訂屬性。 |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | 設定具名的 DateTime 自訂屬性。 |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | 設定具名的字串自訂屬性。 |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | 設定具名的浮點自訂屬性。 |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | 設定具名的雙精度自訂屬性。 |
| [getSensitivityLabels()](#getSensitivityLabels--) | 從自訂文件屬性（Microsoft Information Protection SDK Metadata）取得敏感度標籤陣列。 |
### getAppVersion() {#getAppVersion--}
``` 
public abstract String getAppVersion() 
```

返回應用程式版本。唯讀 String。

--------------------

此元素的內容必須為 XX.YYYY 形式，其中 X 與 Y 為數值；否則，文件將被視為不符合規範。Aspose.Slides 以 XX.YY.ZZ 格式表示其版本，其中：XX - 主要版本 YY - 次要版本 ZZ - 修補版本。例如，值 23.0105 代表 Aspose.Slides 版本 23.1.5。

**返回：**
java.lang.String
### getNameOfApplication() {#getNameOfApplication--}
``` 
public abstract String getNameOfApplication() 
```

返回或設定應用程式的名稱。可讀寫 String。

**返回：**
java.lang.String
### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
``` 
public abstract void setNameOfApplication(String value) 
```

返回或設定應用程式的名稱。可讀寫 String。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getCompany() {#getCompany--}
``` 
public abstract String getCompany() 
```

返回或設定公司屬性。可讀寫 String。

**返回：**
java.lang.String
### setCompany(String value) {#setCompany-java.lang.String-}
``` 
public abstract void setCompany(String value) 
```

返回或設定公司屬性。可讀寫 String。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getManager() {#getManager--}
``` 
public abstract String getManager() 
```

返回或設定管理者屬性。可讀寫 String。

**返回：**
java.lang.String
### setManager(String value) {#setManager-java.lang.String-}
``` 
public abstract void setManager(String value) 
```

返回或設定管理者屬性。可讀寫 String。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getPresentationFormat() {#getPresentationFormat--}
``` 
public abstract String getPresentationFormat() 
```

返回或設定簡報的目標格式。可讀寫 String。

**返回：**
java.lang.String
### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
``` 
public abstract void setPresentationFormat(String value) 
```

返回或設定簡報的目標格式。可讀寫 String。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getSharedDoc() {#getSharedDoc--}
```
public abstract boolean getSharedDoc()
```

判斷簡報是否在多位使用者之間共用。可讀寫 boolean。

**返回：**
boolean
### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public abstract void setSharedDoc(boolean value)
```

判斷簡報是否在多位使用者之間共用。可讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getApplicationTemplate() {#getApplicationTemplate--}
```
public abstract String getApplicationTemplate()
```

返回或設定應用程式的範本。可讀寫 String。

**返回：**
java.lang.String
### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
``` 
public abstract void setApplicationTemplate(String value) 
```

返回或設定應用程式的範本。可讀寫 String。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getTotalEditingTime() {#getTotalEditingTime--}
``` 
public abstract double getTotalEditingTime() 
```

簡報的總編輯時間。可讀寫 double。

**返回：**
double
### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public abstract void setTotalEditingTime(double value)
```

簡報的總編輯時間。可讀寫 double。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |

### getTitle() {#getTitle--}
```
public abstract String getTitle()
```

返回或設定簡報的標題。可讀寫 String。

**返回：**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public abstract void setTitle(String value)
```

返回或設定簡報的標題。可讀寫 String。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getSubject() {#getSubject--}
```
public abstract String getSubject()
```

返回或設定簡報的主題。可讀寫 String。

**返回：**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public abstract void setSubject(String value)
```

返回或設定簡報的主題。可讀寫 String。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getAuthor() {#getAuthor--}
```
public abstract String getAuthor()
```

返回或設定簡報的作者。可讀寫 String。

**返回：**
java.lang.String
### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public abstract void setAuthor(String value)
```

返回或設定簡報的作者。可讀寫 String。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getKeywords() {#getKeywords--}
```
public abstract String getKeywords()
```

返回或設定簡報的關鍵字。可讀寫 String。

**返回：**
java.lang.String
### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public abstract void setKeywords(String value)
```

返回或設定簡報的關鍵字。可讀寫 String。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public abstract String getComments()
```

返回或設定簡報的註解。可讀寫 String。

**返回：**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public abstract void setComments(String value)
```

返回或設定簡報的註解。可讀寫 String。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getCategory() {#getCategory--}
```
public abstract String getCategory()
```

返回或設定簡報的類別。可讀寫 String。

**返回：**
java.lang.String
### setCategory(String value) {#setCategory-java.lang.String-}
```
public abstract void setCategory(String value)
```

返回或設定簡報的類別。可讀寫 String。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```

返回簡報建立的日期。值以 UTC 為單位。可讀寫 java.util.Date。

**返回：**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```

返回簡報建立的日期。值以 UTC 為單位。可讀寫 java.util.Date。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedTime() {#getLastSavedTime--}
```
public abstract Date getLastSavedTime()
```

返回簡報最後修改的日期。值以 UTC 為單位。唯讀（在 Presentation.DocumentProperties 中，因為在 IPresentation 物件保存過程中會內部更新）。可透過方法 [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) 取得的 DocumentProperties 實例變更。請參考 [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-) 方法摘要中的範例。

**返回：**
java.util.Date
### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public abstract void setLastSavedTime(Date value)
```

返回簡報最後修改的日期。值以 UTC 為單位。唯讀（在 Presentation.DocumentProperties 中，因為在 IPresentation 物件保存過程中會內部更新）。可透過方法 [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) 取得的 DocumentProperties 實例變更。請參考 [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-) 方法摘要中的範例。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastPrinted() {#getLastPrinted--}
```
public abstract Date getLastPrinted()
```

返回簡報最後一次列印的日期。可讀寫 java.util.Date。

**返回：**
java.util.Date
### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public abstract void setLastPrinted(Date value)
```

返回簡報最後一次列印的日期。可讀寫 java.util.Date。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedBy() {#getLastSavedBy--}
```
public abstract String getLastSavedBy()
```

返回或設定最後修改簡報之人的名稱。可讀寫 String。

**返回：**
java.lang.String
### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public abstract void setLastSavedBy(String value)
```

返回或設定最後修改簡報之人的名稱。可讀寫 String。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getRevisionNumber() {#getRevisionNumber--}
```
public abstract int getRevisionNumber()
```

返回或設定簡報的修訂號碼。可讀寫 int。

**返回：**
int
### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public abstract void setRevisionNumber(int value)
```

返回或設定簡報的修訂號碼。可讀寫 int。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getContentStatus() {#getContentStatus--}
```
public abstract String getContentStatus()
```

返回或設定簡報的內容狀態。可讀寫 String。

**返回：**
java.lang.String
### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public abstract void setContentStatus(String value)
```

返回或設定簡報的內容狀態。可讀寫 String。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

返回或設定簡報的內容類型。可讀寫 String。

**返回：**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public abstract void setContentType(String value)
```

返回或設定簡報的內容類型。可讀寫 String。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getHyperlinkBase() {#getHyperlinkBase--}
```
public abstract String getHyperlinkBase()
```

返回或設定 HyperlinkBase 文件屬性。可讀寫 String。

**返回：**
java.lang.String
### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public abstract void setHyperlinkBase(String value)
```

返回或設定 HyperlinkBase 文件屬性。可讀寫 String。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getScaleCrop() {#getScaleCrop--}
```
public abstract boolean getScaleCrop()
```

指示文件縮圖的顯示模式。將此元素設定為 **true** 以啟用縮放文件縮圖以符合顯示。將此元素設定為 **false** 以啟用裁剪文件縮圖，只顯示符合顯示的區段。可讀寫 boolean。

**返回：**
boolean
### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public abstract void setScaleCrop(boolean value)
```

指示文件縮圖的顯示模式。將此元素設定為 **true** 以啟用縮放文件縮圖以符合顯示。將此元素設定為 **false** 以啟用裁剪文件縮圖，只顯示符合顯示的區段。可讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getLinksUpToDate() {#getLinksUpToDate--}
```
public abstract boolean getScaleCrop()
```

指示文件中的超連結是否為最新。將此元素設定為 **true** 以表示超連結已更新。將此元素設定為 **false** 以表示超連結已過時。可讀寫 boolean。

**返回：**
boolean
### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public abstract void setLinksUpToDate(boolean value)
```

指示文件中的超連結是否為最新。將此元素設定為 **true** 以表示超連結已更新。將此元素設定為 **false** 以表示超連結已過時。可讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public abstract boolean getHyperlinksChanged()
```

指定此部分中的一個或多個超連結已由產生者僅在此部分更新。下一個開啟此文件的產生者應使用此部分中指定的新超連結更新超連結關係。可讀寫 boolean。

**返回：**
boolean
### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public abstract void setHyperlinksChanged(boolean value)
```

指定此部分中的一個或多個超連結已由產生者僅在此部分更新。下一個開啟此文件的產生者應使用此部分中指定的新超連結更新超連結關係。可讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getSlides() {#getSlides--}
```
public abstract int getSlides()
```

指定簡報文件中投影片的總數。唯讀 int。

**返回：**
int
### getHiddenSlides() {#getHiddenSlides--}
```
public abstract int getHiddenSlides()
```

指定簡報文件中隱藏投影片的數量。唯讀 int。

**返回：**
int
### getNotes() {#getNotes--}
```
public abstract int getNotes()
```

指定簡報中包含備註的投影片數量。唯讀 int。

**返回：**
int
### getParagraphs() {#getParagraphs--}
```
public abstract int getParagraphs()
```

指定文件中找到的段落總數（如適用）。唯讀 int。

**返回：**
int
### getWords() {#getWords--}
```
public abstract int getWords()
```

指定文件中包含的單詞總數。唯讀 int。

**返回：**
int
### getMultimediaClips() {#getMultimediaClips--}
```
public abstract int getMultimediaClips()
```

指定文件中存在的音訊或影片剪輯的總數。唯讀 int。

**返回：**
int
### getTitlesOfParts() {#getTitlesOfParts--}
```
public abstract String[] getTitlesOfParts()
```

指定每個文件部分的標題。這些並非實際的文件部分，而是文件區段的概念表示。唯讀 String[]。

**返回：**
java.lang.String[]
### getHeadingPairs() {#getHeadingPairs--}
```
public abstract IHeadingPair[] getHeadingPairs()
```

指示文件部分的分組以及每組的部分數量。唯讀 IHeadingPair[]。

**返回：**
com.aspose.slides.IHeadingPair[]
### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public abstract int getCountOfCustomProperties()
```

返回集合中實際包含的自訂屬性數量。唯讀 int。

**返回：**
int
### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public abstract String getCustomPropertyName(int index)
```

返回指定索引處的自訂屬性名稱。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要取得的自訂屬性之零基索引。 |

**返回：**
java.lang.String - 指定索引處的自訂屬性名稱。
### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public abstract boolean removeCustomProperty(String name)
```

移除與指定名稱相關聯的自訂屬性。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 要移除的自訂屬性名稱。 |

**返回：**
boolean - 若屬性已被移除則返回 true，否則返回 false。
### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
``` 
public abstract boolean containsCustomProperty(String name) 
```

檢查是否存在指定名稱的自訂屬性。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 要檢查的自訂屬性名稱。 |

**返回：**
boolean - 若屬性存在返回 true，否則返回 false。
### get_Item(String name) {#get-Item-java.lang.String-}
``` 
public abstract Object get_Item(String name) 
```

返回或設定與指定名稱相關聯的自訂屬性。可讀寫 Object。

--------------------

值可以是 **int**、**float**、**double**、**String**、**boolean** 或 **Date**。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String |  |

**返回：**
java.lang.Object
### set_Item(String name, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public abstract void set_Item(String name, Object value)
```

返回或設定與指定名稱相關聯的自訂屬性。可讀寫 Object。

--------------------

值可以是 **int**、**float**、**double**、**String**、**boolean** 或 **Date**。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String |  |
| value | java.lang.Object |  |

### clearCustomProperties() {#clearCustomProperties--}
```
public abstract void clearCustomProperties()
```

移除所有自訂屬性。

### clearBuiltInProperties() {#clearBuiltInProperties--}
```
public abstract void clearBuiltInProperties()
```

清除並設定所有內建屬性的預設值。

### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public abstract void getCustomPropertyValue(String name, boolean[] value)
```

取得自訂屬性中的具名布林值。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 要取得的自訂屬性名稱 |
| value | boolean[] | 自訂屬性值 |

### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public abstract void getCustomPropertyValue(String name, int[] value)
```

取得自訂屬性中的具名整數值。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 要取得的自訂屬性名稱 |
| value | int[] | 自訂屬性值 |

### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public abstract void getCustomPropertyValue(String name, Date[] value)
```

取得自訂屬性中的具名 DateTime 值。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 要取得的自訂屬性名稱 |
| value | java.util.Date[] | 自訂屬性值 |

### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public abstract void getCustomPropertyValue(String name, String[] value)
```

取得自訂屬性中的具名字串值。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 要取得的自訂屬性名稱 |
| value | java.lang.String[] | 自訂屬性值 |

### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public abstract void getCustomPropertyValue(String name, float[] value)
```

取得自訂屬性中的具名浮點值。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 要取得的自訂屬性名稱 |
| value | float[] | 自訂屬性值 |

### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
``` 
public abstract void getCustomPropertyValue(String name, double[] value) 
```

取得自訂屬性中的具名雙精度值。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 要取得的自訂屬性名稱。 |
| value | double[] | 自訂屬性值 |

### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public abstract void setCustomPropertyValue(String name, boolean value)
```

設定具名的布林自訂屬性。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 要設定的自訂屬性名稱 |
| value | boolean | 自訂屬性值 |

### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public abstract void setCustomPropertyValue(String name, int value)
```

設定具名的整數自訂屬性。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 要設定的自訂屬性名稱 |
| value | int | 自訂屬性值 |

### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public abstract void setCustomPropertyValue(String name, Date value)
```

設定具名的 DateTime 自訂屬性。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 要設定的自訂屬性名稱 |
| value | java.util.Date | 自訂屬性值 |

### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public abstract void setCustomPropertyValue(String name, String value)
```

設定具名的字串自訂屬性。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 要設定的自訂屬性名稱 |
| value | java.lang.String | 自訂屬性值 |

### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
``` 
public abstract void setCustomPropertyValue(String name, float value) 
```

設定具名的浮點自訂屬性。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 要設定的自訂屬性名稱 |
| value | float | 自訂屬性值 |

### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public abstract void setCustomPropertyValue(String name, double value)
```

設定具名的雙精度自訂屬性。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 要設定的自訂屬性名稱 |
| value | double | 自訂屬性值 |

### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabel[] getSensitivityLabels()
```

取得自訂文件屬性（Microsoft Information Protection SDK Metadata）中的敏感度標籤陣列。

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