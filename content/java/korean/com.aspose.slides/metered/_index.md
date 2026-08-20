---
title: Metered
second_title: Aspose.Slides for Java API 레퍼런스
description: 계량 키를 설정하는 메서드를 제공합니다.
type: docs
url: /ko/com.aspose.slides/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

계량 키를 설정하는 메서드를 제공합니다.
## Constructors

| Constructor | Description |
| --- | --- |
| [Metered()](#Metered--) | 이 클래스의 새 인스턴스를 초기화합니다. |
## Methods

| Method | Description |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | 계량 공개 및 개인 키를 설정합니다. |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | 소비 파일 크기를 가져옵니다. |
| [getConsumptionCredit()](#getConsumptionCredit--) | 소비 크레딧을 가져옵니다. |
| [isMeteredLicensed()](#isMeteredLicensed--) | 계량이 라이선스가 있는지 확인합니다. |
### Metered() {#Metered--}
```
public Metered()
```


이 클래스의 새 인스턴스를 초기화합니다.

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```


계량 공개 및 개인 키를 설정합니다. 계량 라이선스를 구매한 경우, 애플리케이션을 시작할 때 이 API를 호출해야 하며, 일반적으로 이것만으로 충분합니다. 하지만 소비 데이터를 계속 업로드하지 못하고 24시간이 초과되면 라이선스가 평가 상태로 전환됩니다. 이러한 경우를 방지하려면 라이선스 상태를 정기적으로 확인하고, 평가 상태인 경우 이 API를 다시 호출해야 합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| publicKey | java.lang.String | 공개 키 |
| privateKey | java.lang.String | 개인 키 |

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


소비 파일 크기를 가져옵니다.

**반환값:**
double
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


소비 크레딧을 가져옵니다.

**반환값:**
double - 소비량
### isMeteredLicensed() {#isMeteredLicensed--}
```
public static boolean isMeteredLicensed()
```


계량이 라이선스가 있는지 확인합니다.

**반환값:**
boolean - True 또는 false