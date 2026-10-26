---
title: enclose method
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.mathtext/mathdelimiter/enclose/
weight: 60
---
## enclose(self) {#}
يَلف عنصر رياضي بين قوسين

### القيمة المرجعة

عنصر رياضي من النوع [`IMathDelimiter`](/slides/python-net/ar/aspose.slides.mathtext/imathdelimiter) والذي يتضمن القوسين



```python
def enclose(self):
    ...
```



## enclose(self, beginning_character, ending_character) {#char-char}
يَلف عنصر رياضي بأحرف محددة مثل القوس أو أحرف أخرى كإطار

### القيمة المرجعة

If `beginning_character` and `ending_character` are None, 
            تُعيّن الخصائص المقابلة قيمًا فقط ولا يُنشأ كائن جديد (يرجع هذا الكائن).
            وإلا، يرجع عنصر رياضي جديد من النوع Delimiter يتضمن الأحرف المحددة كإطار 
            وهذا المثال من [`MathDelimiter`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter) داخل الإطار.



```python
def enclose(self, beginning_character, ending_character):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| beginning_character | **char** | الحرف الابتدائي (عادةً القوس الأيسر) |
| ending_character | **char** | الحرف النهائي (عادةً القوس الأيمن) |



### انظر أيضًا
* الفئة [`IMathDelimiter`](/slides/python-net/ar/aspose.slides.mathtext/imathdelimiter)
* الفئة [`MathDelimiter`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter)
* الوحدة [`aspose.slides.mathtext`](/slides/python-net/ar/aspose.slides.mathtext)
* المكتبة [`Aspose.Slides`](/slides/python-net)