---
title: ITemplateEngine
second_title: Aspose.Slides용 Java API 참조
description: 템플릿과 데이터를 쌍으로 변환하여 보통 HTML인 결과 출력물을 만드는 템플릿 엔진을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/itemplateengine/
---```
public interface ITemplateEngine
```

템플릿과 데이터 쌍을 변환하여 결과 출력물(보통 HTML)을 생성하는 템플릿 엔진을 나타냅니다.
## 메서드

| Method | Description |
| --- | --- |
| [addTemplate(String key, String template, System.Type modelType)](#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-) | 템플릿 컬렉션에 템플릿을 추가합니다. |
| [compile(String key, Object model)](#compile-java.lang.String-java.lang.Object-) | 지정된 키와 모델 객체를 사용하여 템플릿을 변환하고 출력물을 생성합니다. |
### addTemplate(String key, String template, System.Type modelType) {#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-}
```
public abstract void addTemplate(String key, String template, System.Type modelType)
```

템플릿 컬렉션에 템플릿을 추가합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | 템플릿 컬렉션에서 템플릿의 키. |
| template | java.lang.String | 템플릿 내용. |
| modelType | com.aspose.ms.System.Type | 템플릿에 대한 모델 객체의 유형. |

### compile(String key, Object model) {#compile-java.lang.String-java.lang.Object-}
```
public abstract String compile(String key, Object model)
```

지정된 키와 모델 객체를 사용하여 템플릿을 변환하고 출력물을 생성합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | 템플릿 컬렉션에서 템플릿의 키. |
| model | java.lang.Object | 변환에 사용할 데이터가 포함된 모델 객체. |

**반환값:**
java.lang.String - 문자열 형태의 결과 출력물.