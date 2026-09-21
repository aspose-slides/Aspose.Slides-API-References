---
title: apply_default_paragraph_indents_shifts method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/bulletformat/apply_default_paragraph_indents_shifts/
weight: 10
---
## apply_default_paragraph_indents_shifts(self) {#}
기본값이 아닌 비-영(0이 아닌) 이동을 설정하여 글머리표가 활성화된 경우 효과적인 단락 Indent와 MarginLeft에 적용합니다(예: PowerPoint에서 단락 글머리표/번호 매기를 활성화하면 동작). 글머리표가 비활성화된 경우 단순히 단락 Indent와 MarginLeft를 재설정합니다(PowerPoint에서 단락 글머리표/번호 매기를 비활성화하면 동작). Indent 이동은 현재 글머리표 컨텍스트인 IBulletFormat.Type, .NumberedBulletStyle 및 첫 번째 부분의 FontHeight를 기준으로 적용됩니다. 비-영(0이 아닌) Indent 이동은 현재 단락의 효과적인 Indent와 MarginLeft에 적용되어 결과 값을 로컬 값으로 만듭니다.

```python
def apply_default_paragraph_indents_shifts(self):
    ...
```

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 이 메서드를 호출해도 상관없으며 다음 경우에 **System.InvalidOperationException**을 발생시킵니다:<br/>            if parent formatted object is not a paragraph (for example calling ITextStyle.DefaultParagraphFormat.Bullet.ApplyDefaultParagraphIndentsShifts() will throw exception);<br/>            or if paragraph wasn't added to any ITextFrame.Paragraphs collection (add it first); |

### 참고
* 클래스 [`BulletFormat`](/slides/python-net/ko/aspose.slides/bulletformat)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)