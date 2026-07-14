---
title: Images
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 인스턴스를 생성하고 작업하기 위한 메서드.
type: docs
url: /ko/com.aspose.slides/images/
---
**상속:**
java.lang.Object
```
public class Images
```

인스턴스를 생성하고 [IImage](../../com.aspose.slides/iimage)와 작업하기 위한 메서드.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Images()](#Images--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [fromData(byte[] imageData)](#fromData-byte---) | 바이트 배열에서 이미지를 생성합니다. |
| [fromFile(String filename)](#fromFile-java.lang.String-) | 파일에서 이미지를 생성합니다. |
| [fromStream(InputStream stream)](#fromStream-java.io.InputStream-) | 스트림에서 이미지를 생성합니다. |
### Images() {#Images--}
```
public Images()
```


### fromData(byte[] imageData) {#fromData-byte---}
```
public static IImage fromData(byte[] imageData)
```


바이트 배열에서 이미지를 생성합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| imageData | byte[] |  |

**반환값:**
[IImage](../../com.aspose.slides/iimage)
### fromFile(String filename) {#fromFile-java.lang.String-}
```
public static IImage fromFile(String filename)
```


파일에서 이미지를 생성합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filename | java.lang.String |  |

**반환값:**
[IImage](../../com.aspose.slides/iimage)
### fromStream(InputStream stream) {#fromStream-java.io.InputStream-}
```
public static IImage fromStream(InputStream stream)
```


스트림에서 이미지를 생성합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | java.io.InputStream |  |

**반환값:**
[IImage](../../com.aspose.slides/iimage)