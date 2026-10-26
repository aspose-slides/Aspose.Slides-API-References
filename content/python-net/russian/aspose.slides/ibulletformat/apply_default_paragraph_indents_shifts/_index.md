---
title: apply_default_paragraph_indents_shifts method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/ibulletformat/apply_default_paragraph_indents_shifts/
weight: 10
---
## apply_default_paragraph_indents_shifts(self) {#}
Устанавливает значения по умолчанию, отличные от нуля, для эффективных параметров параграфа Indent и MarginLeft, когда включены bullets (как PowerPoint делает при включении маркированных списков/нумерации). Если bullets отключены, то просто сбрасывает параметры параграфа Indent и MarginLeft (как PowerPoint делает при отключении маркированных списков/нумерации). Indents shifts применяются с учётом текущего контекста bullet — IBulletFormat.Type, .NumberedBulletStyle и FontHeight первой части. Сдвиги, отличные от нуля, применяются к эффективным параметрам Indent и MarginLeft текущего параграфа (результирующие значения становятся локальными).


```python
def apply_default_paragraph_indents_shifts(self):
    ...
```


### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Вызов этого метода не имеет значения и бросает **System.InvalidOperationException** в следующих случаях:<br/>            если родительский отформатированный объект не является параграфом (например, вызов ITextStyle.DefaultParagraphFormat.Bullet.ApplyDefaultParagraphIndentsShifts() вызовет исключение);<br/>            или если параграф не был добавлен в коллекцию ITextFrame.Paragraphs (добавьте его сначала); |



### См. также
* класс [`IBulletFormat`](/slides/python-net/ru/aspose.slides/ibulletformat)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)