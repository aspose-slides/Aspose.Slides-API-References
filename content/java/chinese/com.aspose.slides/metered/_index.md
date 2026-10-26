---
title: Metered
second_title: Aspose.Slides for Java API 参考
description: 提供设置计量密钥的方法。
type: docs
url: /zh/com.aspose.slides/metered/
---
**继承:**  
java.lang.Object  
```
public class Metered
```

提供设置计量密钥的方法。  
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Metered()](#Metered--) | 初始化此类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | 设置计量公钥和私钥。 |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | 获取消耗文件大小 |
| [getConsumptionCredit()](#getConsumptionCredit--) | 获取消耗积分 |
| [isMeteredLicensed()](#isMeteredLicensed--) | 检查计量是否已授权 |
### Metered() {#Metered--}
```
public Metered()
```

初始化此类的新实例。

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```

设置计量公钥和私钥。如果您购买了计量授权，在启动应用程序时应调用此 API，通常这就足够了。然而，如果始终无法上传消耗数据并超过 24 小时，许可证将被设置为评估状态，为避免此情况，您应定期检查许可证状态，如果是评估状态，请再次调用此 API。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| publicKey | java.lang.String | 公钥 |
| privateKey | java.lang.String | 私钥 |

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```

获取消耗文件大小

**返回:**
double
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```

获取消耗积分

**返回:**
double - 消耗数量
### isMeteredLicensed() {#isMeteredLicensed--}
```
public static boolean isMeteredLicensed()
```

检查计量是否已授权

**返回:**
boolean - True 或 false