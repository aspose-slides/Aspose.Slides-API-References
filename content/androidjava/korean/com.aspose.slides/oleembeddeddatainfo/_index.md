---
title: OleEmbeddedDataInfo
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: OLE 개체에 대한 임베디드 데이터 정보를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/oleembeddeddatainfo/
---
**상속:**  
java.lang.Object

**구현된 모든 인터페이스:**  
[com.aspose.slides.IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)  
```
public class OleEmbeddedDataInfo implements IOleEmbeddedDataInfo
```

OLE 개체에 대한 임베디드 데이터 정보를 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [OleEmbeddedDataInfo()](#OleEmbeddedDataInfo--) | OLE 개체에 대한 새 임베디드 데이터 정보를 생성합니다. |
| [OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)](#OleEmbeddedDataInfo-byte---java.lang.String-) | OLE 개체에 대한 임베디드 데이터 정보의 새 인스턴스를 생성합니다. |

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getEmbeddedFileData()](#getEmbeddedFileData--) | 임베디드 OLE 개체의 파일 데이터를 반환합니다. 읽기 전용 byte[]. |
| [getEmbeddedFileExtension()](#getEmbeddedFileExtension--) | 현재 임베디드 OLE 개체의 파일 확장자를 반환합니다. 읽기 전용 String. |

### OleEmbeddedDataInfo() {#OleEmbeddedDataInfo--}
```
public OleEmbeddedDataInfo()
```

OLE 개체에 대한 새 임베디드 데이터 정보를 생성합니다.

### OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension) {#OleEmbeddedDataInfo-byte---java.lang.String-}
```
public OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)
```

OLE 개체에 대한 임베디드 데이터 정보의 새 인스턴스를 생성합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| embeddedFileData | byte[] | 임베디드 OLE 개체의 파일 데이터 byte[]. |
| embeddedFileExtension | java.lang.String | 현재 임베디드 OLE 개체의 파일 확장자 String. |

### getEmbeddedFileData() {#getEmbeddedFileData--}
```
public final byte[] getEmbeddedFileData()
```

임베디드 OLE 개체의 파일 데이터를 반환합니다. 읽기 전용 byte[].

**반환값:**
byte[]

### getEmbeddedFileExtension() {#getEmbeddedFileExtension--}
```
public final String getEmbeddedFileExtension()
```

현재 임베디드 OLE 개체의 파일 확장자를 반환합니다. 읽기 전용 String.

**반환값:**
java.lang.String