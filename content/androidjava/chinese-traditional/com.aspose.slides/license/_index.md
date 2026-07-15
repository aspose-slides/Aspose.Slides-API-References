---
title: License
second_title: Aspose.Slides for Android via Java API 參考
description: 提供授權此元件的方法。
type: docs
url: /zh-hant/com.aspose.slides/license/
---
**繼承：**
java.lang.Object

**所有已實作的介面：**
[com.aspose.slides.ILicense](../../com.aspose.slides/ilicense)
```
public final class License implements ILicense
```

提供授權此元件的方法。

```
在此範例中，將嘗試尋找名為 MyLicense.lic 的授權檔案
 在包含元件的資料夾、包含呼叫組件的資料夾、入口組件的資料夾，最後在呼叫組件的嵌入式資源中。
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```

## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [License()](#License--) | 初始化此類別的新執行個體。 |
## 方法

| 方法 | 說明 |
| --- | --- |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | 授權此元件。 |
| [setLicense(String namePath)](#setLicense-java.lang.String-) | 授權此元件。 |
| [getVersion()](#getVersion--) | 傳回 Aspose.Slides for Android 的版本（透過 Java）。 |
| [resetLicense()](#resetLicense--) | 重設授權。 |
| [isLicensed()](#isLicensed--) |  |
### License() {#License--}
```
public License()
```

初始化此類別的新執行個體。

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```


### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream stream)
```

授權此元件。

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | java.io.InputStream | 包含授權的資料流。使用 null 以切換至評估模式。 |

### setLicense(String namePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String namePath)
```

授權此元件。

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| namePath | java.lang.String | 可以是完整或簡短的檔案名稱，或嵌入式資源的名稱。使用空字串以切換至評估模式。 |

### getVersion() {#getVersion--}
```
public static final String getVersion()
```

傳回 Aspose.Slides for Android 的版本（透過 Java）。

**傳回：**
java.lang.String
### resetLicense() {#resetLicense--}
```
public final void resetLicense()
```

重設授權。使用此方法在元件中重設授權。

--------------------

> ```
> License license = new License();
>  license.resetLicense();
> ```


### isLicensed() {#isLicensed--}
```
public final boolean isLicensed()
```

檢查是否已在元件上套用授權

**傳回：**
boolean