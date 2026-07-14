---
title: ILinkEmbedController
second_title: Aspose.Slides for Android via Java API Reference
description: 저장 중에 객체가 어떻게 처리되어야 하는지를 결정하는 콜백 인터페이스.
type: docs
url: /ko/com.aspose.slides/ilinkembedcontroller/
---```
public interface ILinkEmbedController
```

저장 중에 객체가 어떻게 처리되어야 하는지를 결정하는 콜백 인터페이스.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)](#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-) | 객체가 저장될 위치를 결정합니다. |
| [getUrl(int id, int referrer)](#getUrl-int-int-) | 외부 객체에 대한 URL을 반환합니다. |
| [saveExternal(int id, byte[] entityData)](#saveExternal-int-byte---) | 외부 객체를 저장합니다. |
### getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension) {#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-}
```
public abstract int getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)
```


객체가 저장될 위치를 결정합니다. 이 메서드는 각 객체 id마다 한 번 호출됩니다. 동일한 데이터, semanticName 및 contentType을 가진 두 객체가 다른 id를 가질 수 있다는 보장은 없습니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| id | int | 객체 id입니다. 이 id는 저장 작업 전체에서 고유합니다. |
| entityData | byte[] | 객체 바이너리 데이터입니다. 객체 바이너리 데이터가 아직 생성되지 않은 경우 이 매개변수는 null일 수 있습니다. |
| semanticName | java.lang.String | 객체의 의미를 설명하는 짧은 텍스트입니다. 컨트롤러는 이를 외부 객체 이름의 일부로 사용할 수 있지만, 이름이 고유하고 허용된 문자만 포함하도록 보장하는 것은 디스패처의 책임입니다. |
| contentType | java.lang.String | 객체의 MIME 타입입니다. |
| recomendedExtension | java.lang.String | 이 MIME 타입에 권장되는 파일 이름 확장자입니다. |

**반환값:**
int - 결정
### getUrl(int id, int referrer) {#getUrl-int-int-}
```
public abstract String getUrl(int id, int referrer)
```


외부 객체에 대한 URL을 반환합니다. 이 메서드는 항상 \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) 가 [LinkEmbedDecision.Link](../../com.aspose.slides/linkembeddecision\#Link) 를 반환했을 때 호출되며, \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) 가 [LinkEmbedDecision.Embed](../../com.aspose.slides/linkembeddecision\#Embed) 를 반환했지만 임베딩이 불가능한 경우에도 호출될 수 있습니다. 동일한 객체 id에 대해 여러 번 호출될 수 있습니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| id | int | 객체 id입니다. 이 id는 저장 작업 전체에서 고유합니다. |
| referrer | int | 참조 객체의 id 또는 루트 문서가 객체를 참조하는 경우 0입니다. 상대 링크를 생성할 때 사용할 수 있습니다. |

**반환값:**
java.lang.String - 외부 객체의 URL 또는 이 객체를 무시해야 하는 경우 null.
### saveExternal(int id, byte[] entityData) {#saveExternal-int-byte---}
```
public abstract void saveExternal(int id, byte[] entityData)
```


외부 객체를 저장합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| id | int | 객체 id입니다. 이 id는 저장 작업 전체에서 고유합니다. |
| entityData | byte[] | 객체 바이너리 데이터입니다. 이 매개변수는 null일 수 없습니다. |