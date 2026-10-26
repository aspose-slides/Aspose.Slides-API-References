---
title: FieldType
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示一種欄位類型。
type: docs
url: /zh-hant/com.aspose.slides/fieldtype/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IFieldType](../../com.aspose.slides/ifieldtype)  
```
public final class FieldType implements IFieldType
```

表示一種欄位類型。此值決定在更新時將設定於欄位部份的文字。

## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [FieldType(String str)](#FieldType-java.lang.String-) | 初始化 FieldType 類別的新執行個體。 |

## 方法

| 方法 | 說明 |
| --- | --- |
| [getInternalString()](#getInternalString--) | 傳回此 FieldType 物件的內部名稱。 |
| [setInternalString(String value)](#setInternalString-java.lang.String-) | 傳回此 FieldType 物件的內部名稱。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 檢查此欄位是否等於另一個。 |
| [hashCode()](#hashCode--) | 傳回此物件的雜湊碼。 |
| [op_Equality(FieldType a, FieldType b)](#op-Equality-com.aspose.slides.FieldType-com.aspose.slides.FieldType-) | 檢查兩個 FieldType 物件是否相等。 |
| [op_Inequality(FieldType a, FieldType b)](#op-Inequality-com.aspose.slides.FieldType-com.aspose.slides.FieldType-) | 檢查兩個 FieldType 物件是否不相等。 |
| [getSlideNumber()](#getSlideNumber--) | 目前投影片的編號。 |
| [getFooter()](#getFooter--) | 投影片的頁腳。 |
| [getHeader()](#getHeader--) | 投影片的頁首。 |
| [getDateTime()](#getDateTime--) | 目前日期與時間，使用渲染應用程式的預設日期時間格式。 |
| [getDateTime1()](#getDateTime1--) | 目前日期與時間，以第一個預先定義的格式 (MM/DD/YYYY for english)。 |
| [getDateTime2()](#getDateTime2--) | 目前日期與時間，以第二個預先定義的格式 (Day, Month DD, YYYY for english)。 |
| [getDateTime3()](#getDateTime3--) | 目前日期與時間，以第三個預先定義的格式 (DD Month YYYY for english)。 |
| [getDateTime4()](#getDateTime4--) | 目前日期與時間，以第四個預先定義的格式 (Month DD, YYYY for english)。 |
| [getDateTime5()](#getDateTime5--) | 目前日期與時間，以第五個預先定義的格式 (DD-Mon-YY for english)。 |
| [getDateTime6()](#getDateTime6--) | 目前日期與時間，以第六個預先定義的格式 (Month YY for english)。 |
| [getDateTime7()](#getDateTime7--) | 目前日期與時間，以第七個預先定義的格式 (Mon-YY for english)。 |
| [getDateTime8()](#getDateTime8--) | 目前日期與時間，以第八個預先定義的格式 (MM/DD/YYYY hh:mm AM/PM for english)。 |
| [getDateTime9()](#getDateTime9--) | 目前日期與時間，以第九個預先定義的格式 (MM/DD/YYYY hh:mm:ss AM/PM for english)。 |
| [getDateTime10()](#getDateTime10--) | 目前日期與時間，以第十個預先定義的格式 (hh:mm for english)。 |
| [getDateTime11()](#getDateTime11--) | 目前日期與時間，以第十一個預先定義的格式 (hh:mm:ss for english)。 |
| [getDateTime12()](#getDateTime12--) | 目前日期與時間，以第十二個預先定義的格式 (hh:mm AM/PM for english)。 |
| [getDateTime13()](#getDateTime13--) | 目前日期與時間，以第十三個預先定義的格式 (hh:mm:ss AM/PM for english)。 |

### FieldType(String str) {#FieldType-java.lang.String-}
```
public FieldType(String str)
```

初始化 FieldType 類別的新執行個體。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| str | java.lang.String |  |

### getInternalString() {#getInternalString--}
```
public final String getInternalString()
```

傳回此 FieldType 物件的內部名稱。讀寫 String。

**傳回：**
java.lang.String

### setInternalString(String value) {#setInternalString-java.lang.String-}
```
public final void setInternalString(String value)
```

傳回此 FieldType 物件的內部名稱。讀寫 String。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

檢查此欄位是否等於另一個。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | java.lang.Object | 要比較的欄位。 |

**傳回：**
boolean - 若欄位相等則為 True。

### hashCode() {#hashCode--}
```
public int hashCode()
```

傳回此物件的雜湊碼。

**傳回：**
int - 雜湊碼 int。

### op_Equality(FieldType a, FieldType b) {#op-Equality-com.aspose.slides.FieldType-com.aspose.slides.FieldType-}
```
public static boolean op_Equality(FieldType a, FieldType b)
```

檢查兩個 FieldType 物件是否相等。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| a | [FieldType](../../com.aspose.slides/fieldtype) | 第一個要比較的 FieldType。 |
| b | [FieldType](../../com.aspose.slides/fieldtype) | 第二個要比較的 FieldType。 |

**傳回：**
boolean - 若 FieldType 物件相等則為 True。

### op_Inequality(FieldType a, FieldType b) {#op-Inequality-com.aspose.slides.FieldType-com.aspose.slides.FieldType-}
```
public static boolean op_Inequality(FieldType a, FieldType b)
```

檢查兩個 FieldType 物件是否不相等。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| a | [FieldType](../../com.aspose.slides/fieldtype) | 第一個要比較的 FieldType。 |
| b | [FieldType](../../com.aspose.slides/fieldtype) | 第二個要比較的 FieldType。 |

**傳回：**
boolean - 若 FieldType 物件不相等則為 True。

### getSlideNumber() {#getSlideNumber--}
```
public static FieldType getSlideNumber()
```

目前投影片的編號。唯讀 [FieldType](../../com.aspose.slides/fieldtype)。

**傳回：**
[FieldType](../../com.aspose.slides/fieldtype)

### getFooter() {#getFooter--}
```
public static FieldType getFooter()
```

投影片的頁腳。唯讀 [FieldType](../../com.aspose.slides/fieldtype)。

**傳回：**
[FieldType](../../com.aspose.slides/fieldtype)

### getHeader() {#getHeader--}
```
public static FieldName getHeader()
```

投影片的頁首。唯讀 [FieldType](../../com.aspose.slides/fieldtype)。

**傳回：**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime() {#getDateTime--}
```
public static FieldType getDateTime()
```

目前日期與時間，使用渲染應用程式的預設日期時間格式。唯讀 [FieldType](../../com.aspose.slides/fieldtype)。

**傳回：**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime1() {#getDateTime1--}
```
public static FieldType getDateTime1()
```

目前日期與時間，以第一個預先定義的格式 (MM/DD/YYYY for english)。唯讀 [FieldType](../../com.aspose.slides/fieldtype)。

**傳回：**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime2() {#getDateTime2--}
```
public static FieldType getDateTime2()
```

目前日期與時間，以第二個預先定義的格式 (Day, Month DD, YYYY for english)。唯讀 [FieldType](../../com.aspose.slides/fieldtype)。

**傳回：**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime3() {#getDateTime3--}
```
public static FieldType getDateTime3()
```

目前日期與時間，以第三個預先定義的格式 (DD Month YYYY for english)。唯讀 [FieldType](../../com.aspose.slides/fieldtype)。

**傳回：**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime4() {#getDateTime4--}
```
public static FieldType getDateTime4()
```

目前日期與時間，以第四個預先定義的格式 (Month DD, YYYY for english)。唯讀 [FieldType](../../com.aspose.slides/fieldtype)。

**傳回：**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime5() {#getDateTime5--}
```
public static FieldType getDateTime5()
```

目前日期與時間，以第五個預先定義的格式 (DD-Mon-YY for english)。唯讀 [FieldType](../../com.aspose.slides/fieldtype)。

**傳回：**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime6() {#getDateTime6--}
```
public static FieldType getDateTime6()
```

目前日期與時間，以第六個預先定義的格式 (Month YY for english)。唯讀 [FieldType](../../com.aspose.slides/fieldtype)。

**傳回：**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime7() {#getDateTime7--}
```
public static FieldType getDateTime7()
```

目前日期與時間，以第七個預先定義的格式 (Mon-YY for english)。唯讀 [FieldType](../../com.aspose.slides/fieldtype)。

**傳回：**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime8() {#getDateTime8--}
```
public static FieldType getDateTime8()
```

目前日期與時間，以第八個預先定義的格式 (MM/DD/YYYY hh:mm AM/PM for english)。唯讀 [FieldType](../../com.aspose.slides/fieldtype)。

**傳回：**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime9() {#getDateTime9--}
```
public static FieldType getDateTime9()
```

目前日期與時間，以第九個預先定義的格式 (MM/DD/YYYY hh:mm:ss AM/PM for english)。唯讀 [FieldType](../../com.aspose.slides/fieldtype)。

**傳回：**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime10() {#getDateTime10--}
```
public static FieldType getDateTime10()
```

目前日期與時間，以第十個預先定義的格式 (hh:mm for english)。唯讀 [FieldType](../../com.aspose.slides/fieldtype)。

**傳回：**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime11() {#getDateTime11--}
```
public static FieldType getDateTime11()
```

目前日期與時間，以第十一個預先定義的格式 (hh:mm:ss for english)。唯讀 [FieldType](../../com.aspose.slides/fieldtype)。

**傳回：**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime12() {#getDateTime12--}
```
public static FieldType getDateTime12()
```

目前日期與時間，以第十二個預先定義的格式 (hh:mm AM/PM for english)。唯讀 [FieldType](../../com.aspose.slides/fieldtype)。

**傳回：**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime13() {#getDateTime13--}
```
public static FieldType getDateTime13()
```

目前日期與時間，以第十三個預先定義的格式 (hh:mm:ss AM/PM for english)。唯讀 [FieldType](../../com.aspose.slides/fieldtype)。

**傳回：**
[FieldType](../../com.aspose.slides/fieldtype)