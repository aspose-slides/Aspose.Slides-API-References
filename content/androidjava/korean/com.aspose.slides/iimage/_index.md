---
title: IImage
second_title: Android용 Aspose.Slides Java API 레퍼런스
description: 래스터 또는 벡터 이미지를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/iimage/
---
**모든 구현된 인터페이스:**
com.aspose.ms.System.IDisposable
```
public interface IImage extends System.IDisposable
```

래스터 또는 벡터 이미지를 나타냅니다.

--------------------

이 인터페이스는 래스터와 벡터 이미지를 모두 처리하기 위한 공통 추상화를 제공합니다. 구현은 기본 이미지 유형에 따라 달라질 수 있습니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [save(String filename)](#save-java.lang.String-) | 이미지를 파일에 저장합니다. |
| [save(String filename, int format)](#save-java.lang.String-int-) | 이미지를 지정된 형식으로 파일에 저장합니다. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | 이미지를 지정된 형식으로 스트림에 저장합니다. |
| [save(String filename, int format, int quality)](#save-java.lang.String-int-int-) | 이미지를 지정된 형식 및 품질로 파일에 저장합니다. |
| [save(OutputStream stream, int format, int quality)](#save-java.io.OutputStream-int-int-) | 이미지를 지정된 형식 및 품질로 스트림에 저장합니다. |
| [getSize()](#getSize--) | 이미지의 크기를 가져옵니다. |
| [getWidth()](#getWidth--) | 이미지의 너비를 픽셀 단위로 가져옵니다. |
| [getHeight()](#getHeight--) | 이미지의 높이를 픽셀 단위로 가져옵니다. |
### save(String filename) {#save-java.lang.String-}
```
public abstract void save(String filename)
```


이미지를 파일에 저장합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filename | java.lang.String | 이미지를 저장할 파일의 경로입니다. |

### save(String filename, int format) {#save-java.lang.String-int-}
```
public abstract void save(String filename, int format)
```


이미지를 지정된 형식으로 파일에 저장합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filename | java.lang.String | 이미지를 저장할 파일의 경로입니다. |
| format | int | 이미지 형식입니다. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```


이미지를 지정된 형식으로 스트림에 저장합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | java.io.OutputStream | 이미지를 저장할 스트림입니다. |
| format | int | 이미지 형식입니다. |

### save(String filename, int format, int quality) {#save-java.lang.String-int-int-}
```
public abstract void save(String filename, int format, int quality)
```


이미지를 지정된 형식 및 품질로 파일에 저장합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filename | java.lang.String | 이미지를 저장할 파일의 경로입니다. |
| format | int | 이미지 형식입니다. |
| quality | int | 저장된 이미지의 품질(0~100). 이 매개변수는 [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg) 저장에만 영향을 미치며, 다른 모든 형식에서는 무시됩니다. |

### save(OutputStream stream, int format, int quality) {#save-java.io.OutputStream-int-int-}
```
public abstract void save(OutputStream stream, int format, int quality)
```


이미지를 지정된 형식 및 품질로 스트림에 저장합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | java.io.OutputStream | 이미지를 저장할 스트림입니다. |
| format | int | 이미지 형식입니다. |
| quality | int | 저장된 이미지의 품질(0~100). 이 매개변수는 [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg) 저장에만 영향을 미치며, 다른 모든 형식에서는 무시됩니다. |

### getSize() {#getSize--}
```
public abstract Size getSize()
```


이미지의 크기를 가져옵니다.

**반환:**
[Size](../../com.aspose.slides.android/size)
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


이미지의 너비를 픽셀 단위로 가져옵니다.

**반환:**
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


이미지의 높이를 픽셀 단위로 가져옵니다.

**반환:**
int