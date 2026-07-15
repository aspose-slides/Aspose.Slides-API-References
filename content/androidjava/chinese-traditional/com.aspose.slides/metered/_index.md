---
title: Metered
second_title: Aspose.Slides for Android 的 Java API 參考
description: 提供設定 metered 金鑰的方法。
type: docs
url: /zh-hant/com.aspose.slides/metered/
---
**繼承：**
java.lang.Object
```
public class Metered
```

提供設定 metered 金鑰的方法。
## 建構式

| 建構式 | 描述 |
| --- | --- |
| [Metered()](#Metered--) | 初始化此類別的新執行個體。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | 設定 metered 公鑰與私鑰。 |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | 取得消費文件大小 |
| [getConsumptionCredit()](#getConsumptionCredit--) | 取得消費點數 |
| [isMeteredLicensed()](#isMeteredLicensed--) | 檢查 metered 是否已授權 |
### Metered() {#Metered--}
```
public Metered()
```


初始化此類別的新執行個體。

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```


設定 metered 公鑰與私鑰。如果您購買了 metered 授權，當應用程式啟動時，應該呼叫此 API，通常這已足夠。然而，若始終無法上傳消費資料且超過 24 小時，授權將被設為評估狀態。為避免此情況，您應定期檢查授權狀態，若為評估狀態，請再次呼叫此 API。

**Parameters:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| publicKey | java.lang.String | 公鑰 |
| privateKey | java.lang.String | 私鑰 |

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


取得消費文件大小

**Returns:**
double
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


取得消費點數

**Returns:**
double - 消費量
### isMeteredLicensed() {#isMeteredLicensed--}
```
public static boolean isMeteredLicensed()
```


檢查 metered 是否已授權

**Returns:**
boolean - True 或 false