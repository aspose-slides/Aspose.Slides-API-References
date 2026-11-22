---
title: get_text_rect method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/textframe/get_text_rect/
weight: 10
---
## get_text_rect(self) {#}
Hämtar textrektangeln som definieras av föräldraformens geometri.

### Returns

En [`RectangleF`](/slides/python-net/sv/aspose.slides/rectanglef) som definierar textområdet.



```python
def get_text_rect(self):
    ...
```


### Remarks
Rektangelns koordinater är relativa till föräldraformens övre vänstra hörn.

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Textramen är inte associerad med en geometrisk form. |



### See Also
* klass [`TextFrame`](/slides/python-net/sv/aspose.slides/textframe)
* klass [`RectangleF`](/slides/python-net/sv/aspose.slides/rectanglef)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)