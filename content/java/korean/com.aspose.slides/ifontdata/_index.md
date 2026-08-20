---
title: IFontData
second_title: Aspose.Slides for Java API 참조
description: 폰트 정의를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ifontdata/
---```
public interface IFontData
```

폰트 정의를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFontName()](#getFontName--) | 폰트 이름을 반환합니다. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | 테마 참조를 실제 사용된 폰트로 교체하여 폰트 이름을 반환합니다. |
### getFontName() {#getFontName--}
```
public abstract String getFontName()
```

폰트 이름을 반환합니다. 읽기 전용 String.

**반환값:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public abstract String getFontName(IThemeEffectiveData theme)
```

테마 참조를 실제 사용된 폰트로 교체하여 폰트 이름을 반환합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | 테마화된 폰트 이름을 가져올 테마입니다. 올바른 값을 제공하는 것은 호출자에게 달려 있습니다. |

**반환값:**
java.lang.String - 폰트 이름.