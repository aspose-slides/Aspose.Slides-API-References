---
title: apply_default_paragraph_indents_shifts method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/bulletformat/apply_default_paragraph_indents_shifts/
weight: 10
---
## apply_default_paragraph_indents_shifts(self) {#}
Устанавливает значения сдвигов по умолчанию, отличные от нуля, для эффективных параметров параграфа Indent и MarginLeft, когда включены маркеры (как PowerPoint делает при включении маркеров/нумерации абзаца). Если маркеры отключены, просто сбрасывает параметры параграфа Indent и MarginLeft (как PowerPoint делает при отключении маркеров/нумерации абзаца). Сдвиги отступов применяются с учётом текущего контекста маркера — IBulletFormat.Type, .NumberedBulletStyle и FontHeight первой части. Сдвиги, отличные от нуля, применяются к эффективным параметрам Indent и MarginLeft текущего параграфа (делают результирующие значения локальными).


```python
def apply_default_paragraph_indents_shifts(self):
    ...
```


### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Вызов этого метода не имеет значения и бросает **System.InvalidOperationException** в следующих случаях:<br/>            если родительский отформатированный объект не является абзацем (например, вызов ITextStyle.DefaultParagraphFormat.Bullet.ApplyDefaultParagraphIndentsShifts() вызовет исключение);<br/>            или если абзац не был добавлен в любую коллекцию ITextFrame.Paragraphs (добавьте его сначала); |



### См. также
* класс [`BulletFormat`](/slides/python-net/ru/aspose.slides/bulletformat)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)