---
title: OleEmbeddedDataInfo
second_title: Aspose.Slides for Java API 레퍼런스
description: OLE 객체에 대한 임베디드 데이터 정보를 나타냅니다.
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

OLE 객체에 대한 임베디드 데이터 정보를 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [OleEmbeddedDataInfo()](#OleEmbeddedDataInfo--) | OLE 객체에 대한 새 임베디드 데이터 정보를 생성합니다. |
| [OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)](#OleEmbeddedDataInfo-byte---java.lang.String-) | OLE 객체에 대한 임베디드 데이터 정보의 새 인스턴스를 생성합니다. |

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getEmbeddedFileData()](#getEmbeddedFileData--) | 임베디드 OLE 객체의 파일 데이터를 반환합니다. 읽기 전용 byte[]. |
| [getEmbeddedFileExtension()](#getEmbeddedFileExtension--) | 현재 임베디드 OLE 객체의 파일 확장자를 반환합니다. 읽기 전용 String. |

### OleEmbeddedDataInfo() {#OleEmbeddedDataInfo--}
```
public OleEmbeddedDataInfo()
```

OLE 객체에 대한 새 임베디드 데이터 정보를 생성합니다.

### OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension) {#OleEmbeddedDataInfo-byte---java.lang.String-}
```
public OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)
```

OLE 객체에 대한 임베디드 데이터 정보의 새 인스턴스를 생성합니다.

**매개 변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| embeddedFileData | byte[] | 임베디드 OLE 객체의 파일 데이터 byte[]. |
| embeddedFileExtension | java.lang.String | 현재 임베디드 OLE 객체의 파일 확장자 String. |

### getEmbeddedFileData() {#getEmbeddedFileData--}
```
public final byte[] getEmbeddedFileData()
```

임베디드 OLE 객체의 파일 데이터를 반환합니다. 읽기 전용 byte[].

**반환:**
byte[]

### getEmbeddedFileExtension() {#getEmbeddedFileExtension--}
```
public final String getEmbeddedFileExtension()
```

현재 임베디드 OLE 객체의 파일 확장자를 반환합니다. 읽기 전용 String.

**반환:**
java.lang.String