---
title: ITemplateEngine
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a template engine that transforms template and data pair into resulting output usually HTML.
type: docs
url: /ko/com.aspose.slides/itemplateengine/
---```
public interface ITemplateEngine
```

템플릿과 데이터 쌍을 변환하여 결과 출력(보통 HTML)을 생성하는 템플릿 엔진을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [addTemplate(String key, String template, System.Type modelType)](#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-) | 템플릿을 템플릿 컬렉션에 추가합니다. |
| [compile(String key, Object model)](#compile-java.lang.String-java.lang.Object-) | 주어진 키와 모델 객체를 사용하여 템플릿을 출력으로 변환합니다. |
### addTemplate(String key, String template, System.Type modelType) {#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-}
```
public abstract void addTemplate(String key, String template, System.Type modelType)
```


템플릿을 템플릿 컬렉션에 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| key | java.lang.String | 템플릿 컬렉션에서 템플릿의 키. |
| template | java.lang.String | 템플릿 내용. |
| modelType | com.aspose.ms.System.Type | 템플릿에 대한 모델 객체의 유형. |

### compile(String key, Object model) {#compile-java.lang.String-java.lang.Object-}
```
public abstract String compile(String key, Object model)
```


주어진 키와 모델 객체를 사용하여 템플릿을 출력으로 변환합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| key | java.lang.String | 템플릿 컬렉션에서 템플릿의 키. |
| model | java.lang.Object | 변환을 위한 데이터가 포함된 모델 객체. |

**반환값:**
java.lang.String - 문자열로 결과 출력.