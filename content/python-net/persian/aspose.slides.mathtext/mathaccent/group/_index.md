---
title: group method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.mathtext/mathaccent/group/
weight: 80
---
## group(self) {#}
این عنصر را با استفاده از یک bottom curly bracket در یک گروه قرار می‌دهد

### بازگشت

نمونه جدیدی از نوع [`IMathGroupingCharacter`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
این عنصر را با استفاده از یک کاراکتر گروه‌بندی مانند bottom curly bracket یا کاراکتر دیگری در یک گروه قرار می‌دهد

### بازگشت

نمونه جدیدی از نوع [`IMathGroupingCharacter`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| character | **char** | کاراکتر گروه‌بندی مانند BOTTOM CURLY BRACKET (U+23DF) یا هر کاراکتر دیگری |
| position | [`MathTopBotPositions`](/slides/python-net/fa/aspose.slides.mathtext/mathtopbotpositions) | موقعیت کاراکتر گروه‌بندی |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/fa/aspose.slides.mathtext/mathtopbotpositions) | ترازبندی عمودی کاراکتر گروه.<br/><br/>            ترازبندی شیء نسبت به خط پایه را مشخص می‌کند.<br/><br/>            برای مثال، وقتی کاراکتر گروه بالای شیء باشد، <br/><br/>            VerticalJustification بالا نشان می‌دهد که بالای شیء بر خط پایه قرار دارد؛<br/><br/>            وقتی VerticalJustification به Bottom تنظیم شود، پایین شیء بر خط پایه است. |



### مراجع مرتبط
* کلاس [`IMathGroupingCharacter`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter)
* کلاس [`MathAccent`](/slides/python-net/fa/aspose.slides.mathtext/mathaccent)
* شمارش [`MathTopBotPositions`](/slides/python-net/fa/aspose.slides.mathtext/mathtopbotpositions)
* ماژول [`aspose.slides.mathtext`](/slides/python-net/fa/aspose.slides.mathtext)
* کتابخانه [`Aspose.Slides`](/slides/python-net)