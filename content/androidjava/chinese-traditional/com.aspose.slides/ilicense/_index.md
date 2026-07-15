---
title: ILicense
second_title: Aspose.Slides for Android via Java API Reference
description: 提供授權元件的方法。
type: docs
url: /zh-hant/com.aspose.slides/ilicense/
---```
public interface ILicense
```

提供授權元件的方法。

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>  in the folder that contains the component, in the folder that contains the calling assembly,
>  in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>  
>  License license = new License();
>  license.setLicense("MyLicense.lic");
> ```
## 方法

| 方法 | 描述 |
| --- | --- |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | 授權此元件。 |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | 授權此元件。 |
| [resetLicense()](#resetLicense--) | 重設授權 |
| [isLicensed()](#isLicensed--) | 檢查是否已為元件套用授權 |
### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public abstract void setLicense(String licenseName)
```


授權此元件。

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>  in the folder that contains the component, in the folder that contains the calling assembly,
>  in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>  
>  License license = new License();
>  license.setLicense("MyLicense.lic");
> ```

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| licenseName | java.lang.String | 可以是完整或簡短的檔案名稱或嵌入式資源的名稱。使用空字串切換至評估模式。 |

嘗試在下列位置尋找授權：

1. 明確路徑。

2. 元件組件的資料夾。

3. 客戶端呼叫組件的資料夾。

4. 入口組件的資料夾。

5. 客戶端呼叫組件中的嵌入式資源。 |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public abstract void setLicense(InputStream stream)
```


授權此元件。

--------------------

> ```
> License license = new License();
>  license.setLicense(myStream);
> ```

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 包含授權的資料流。 |

使用此方法從資料流載入授權。 |

### resetLicense() {#resetLicense--}
```
public abstract void resetLicense()
```


重設授權

--------------------

> ```
> License license = new License();
>  license.resetLicense();
> ```

使用此方法在元件中重設授權

### isLicensed() {#isLicensed--}
```
public abstract boolean isLicensed()
```


檢查是否已為元件套用授權

**回傳值:**
boolean - 如果元件已授權則為 true，否則為 false