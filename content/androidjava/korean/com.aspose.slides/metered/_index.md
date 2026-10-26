---
title: Metered
second_title: Java API 레퍼런스를 통한 Aspose.Slides for Android
description: metered 키를 설정하는 메서드를 제공합니다.
type: docs
url: /ko/com.aspose.slides/metered/
---
**상속:**
java.lang.Object
```
public class Metered
```

metered key를 설정하는 메서드를 제공합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Metered()](#Metered--) | 이 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | metered 공개 키와 개인 키를 설정합니다. |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | 소비 파일 크기를 가져옵니다. |
| [getConsumptionCredit()](#getConsumptionCredit--) | 소비 크레딧을 가져옵니다. |
| [isMeteredLicensed()](#isMeteredLicensed--) | metered가 라이선스가 부여되었는지 확인합니다. |
### Metered() {#Metered--}
```
public Metered()
```

이 클래스의 새 인스턴스를 초기화합니다.

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```

metered 공개 키와 개인 키를 설정합니다. metered 라이선스를 구매한 경우 애플리케이션을 시작할 때 이 API를 호출해야 하며, 일반적으로 이것만으로 충분합니다. 그러나 항상 소비 데이터를 업로드하지 못하고 24시간을 초과하면 라이선스가 평가 상태로 설정됩니다. 이러한 경우를 방지하려면 정기적으로 라이선스 상태를 확인하고 평가 상태인 경우 이 API를 다시 호출해야 합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
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

metered가 라이선스가 부여되었는지 확인합니다.

**반환값:**
boolean - True 또는 false