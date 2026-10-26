---
title: apply_default_paragraph_indents_shifts method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/ibulletformat/apply_default_paragraph_indents_shifts/
weight: 10
---
## apply_default_paragraph_indents_shifts(self) {#}
글머리 기호가 활성화된 경우(예: PowerPoint에서 단락 글머리 기호/번호 매기기를 활성화할 때와 같이) 효과적인 단락 Indent와 MarginLeft에 대해 기본 비영(0이 아닌) 이동값을 설정합니다. 글머리 기호가 비활성화된 경우에는 단락 Indent와 MarginLeft를 단순히 재설정합니다(예: PowerPoint에서 단락 글머리 기호/번호 매기기를 비활성화할 때와 같이). Indent 이동값은 현재 글머리 기호 컨텍스트- IBulletFormat.Type, .NumberedBulletStyle 및 첫 번째 구문의 FontHeight- 를 기준으로 적용됩니다. 비영(0이 아닌) indent 이동값은 현재 단락의 효과적인 Indent와 MarginLeft에 적용됩니다(결과 값을 로컬 값으로 만듭니다).


```python
def apply_default_paragraph_indents_shifts(self):
    ...
```


### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 다음과 같은 경우에 이 메서드를 호출하면 **System.InvalidOperationException**이 발생합니다:<br/>            부모 형식화 객체가 단락이 아닌 경우(예: ITextStyle.DefaultParagraphFormat.Bullet.ApplyDefaultParagraphIndentsShifts() 호출 시 예외 발생);<br/>            또는 단락이 어느 ITextFrame.Paragraphs 컬렉션에도 추가되지 않은 경우(먼저 추가하십시오); |



### 참고
* 클래스 [`IBulletFormat`](/slides/python-net/ko/aspose.slides/ibulletformat)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)