---
title: LegacyDiagram
second_title: Справочник API Aspose.Slides для Java
description: Представляет объект устаревшей диаграммы.
type: docs
url: /ru/com.aspose.slides/legacydiagram/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Все реализованные интерфейсы:**
[com.aspose.slides.ILegacyDiagram](../../com.aspose.slides/ilegacydiagram)
```
public class LegacyDiagram extends GraphicalObject implements ILegacyDiagram
```

Представляет объект устаревшей диаграммы.
## Методы

| Метод | Описание |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | Преобразует устаревшую диаграмму в редактируемый объект SmartArt. |
| [convertToGroupShape()](#convertToGroupShape--) | Преобразует устаревшую диаграмму в редактируемую групповую фигуру. |
### convertToSmartArt() {#convertToSmartArt--}
```
public final ISmartArt convertToSmartArt()
```


Преобразует устаревшую диаграмму в редактируемый объект SmartArt. Созданный объект SmartArt добавляется к родительской групповой фигуре на той же позиции.

**Возвращает:**
[ISmartArt](../../com.aspose.slides/ismartart) - Созданный объект SmartArt.
### convertToGroupShape() {#convertToGroupShape--}
```
public final IGroupShape convertToGroupShape()
```


Преобразует устаревшую диаграмму в редактируемую групповую фигуру. Созданный объект GroupShape добавляется к родительской групповой фигуре на той же позиции.

**Возвращает:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Созданный объект GroupShape.