---
title: IOleEmbeddedDataInfo
second_title: Aspose.Slides for Android via Java API Reference
description: OLE 개체에 대한 임베디드 데이터 정보를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ioleembeddeddatainfo/
---```
public interface IOleEmbeddedDataInfo
```

OLE 개체에 대한 임베디드 데이터 정보를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getEmbeddedFileData()](#getEmbeddedFileData--) | 임베디드 OLE 객체의 파일 데이터를 반환합니다. 읽기 전용 byte[]. |
| [getEmbeddedFileExtension()](#getEmbeddedFileExtension--) | 현재 임베디드 OLE 객체의 파일 확장자를 반환합니다. 읽기 전용 String. |
### getEmbeddedFileData() {#getEmbeddedFileData--}
```
public abstract byte[] getEmbeddedFileData()
```

임베디드 OLE 객체의 파일 데이터를 반환합니다. 읽기 전용 byte[].

**반환값:**
byte[]
### getEmbeddedFileExtension() {#getEmbeddedFileExtension--}
```
public abstract String getEmbeddedFileExtension()
```

현재 임베디드 OLE 객체의 파일 확장자를 반환합니다. 읽기 전용 String.

**반환값:**
java.lang.String