---
title: CurrentThreadSettings
second_title: Java API 레퍼런스를 사용한 Android용 Aspose.Slides
description: 현재 스레드에 대한 기본 Locale을 정의할 수 있는 보조 클래스
type: docs
url: /ko/com.aspose.slides/currentthreadsettings/
---
**상속:**
java.lang.Object
```
public class CurrentThreadSettings
```

현재 스레드에 대한 기본 Locale을 정의할 수 있는 보조 클래스
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [CurrentThreadSettings()](#CurrentThreadSettings--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getLocale()](#getLocale--) | 현재 스레드의 기본 Locale을 반환합니다. |
| [setLocale(Locale locale)](#setLocale-java.util.Locale-) | 현재 스레드의 기본 Locale을 설정합니다. |
| [setLocale(String localeName)](#setLocale-java.lang.String-) | 현재 스레드의 기본 Locale을 설정합니다. |
### CurrentThreadSettings() {#CurrentThreadSettings--}
```
public CurrentThreadSettings()
```


### getLocale() {#getLocale--}
```
public static final Locale getLocale()
```


현재 스레드의 기본 Locale을 반환합니다.

**반환:**  
java.util.Locale - 현재 Locale
### setLocale(Locale locale) {#setLocale-java.util.Locale-}
```
public static final void setLocale(Locale locale)
```


현재 스레드의 기본 Locale을 설정합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| locale | java.util.Locale | 현재 스레드의 기본 Locale. |

### setLocale(String localeName) {#setLocale-java.lang.String-}
```
public static final void setLocale(String localeName)
```


현재 스레드의 기본 Locale을 설정합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| localeName | java.lang.String | 현재 스레드의 기본 Locale. |