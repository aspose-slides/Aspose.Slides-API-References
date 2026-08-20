---
title: Metered
second_title: Aspose.Slides for Java API 參考
description: 提供設定計量金鑰的方法。
type: docs
url: /zh-hant/com.aspose.slides/metered/
---
**繼承:**  
java.lang.Object  
```
public class Metered
```

提供設定計量金鑰的方法。  
## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [Metered()](#Metered--) | 初始化此類別的新執行個體。 |
## 方法

| 方法 | 說明 |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | 設定計量公鑰與私鑰。 |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | 取得消耗檔案大小 |
| [getConsumptionCredit()](#getConsumptionCredit--) | 取得消耗信用額度 |
| [isMeteredLicensed()](#isMeteredLicensed--) | 檢查計量是否已取得授權 |
### Metered() {#Metered--}
```
public Metered()
```

初始化此類別的新執行個體。

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```

設定計量公鑰與私鑰。若您購買計量授權，應用程式啟動時必須呼叫此 API，通常這已足夠。然而，如果一直無法上傳消耗資料且超過 24 小時，授權會被設定為評估狀態。為避免此情況，您應定期檢查授權狀態，若為評估狀態，請再次呼叫此 API。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| publicKey | java.lang.String | 公鑰 |
| privateKey | java.lang.String | 私鑰 |

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```

取得消耗檔案大小

**返回值:**
double
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```

取得消耗信用額度

**返回值:**
double - 消耗數量
### isMeteredLicensed() {#isMeteredLicensed--}
```
public static boolean isMeteredLicensed()
```

檢查計量是否已取得授權

**返回值:**
boolean - 真或假