---
title: Camera
second_title: Справочник по API Aspose.Slides для .NET
description: Представляет камеру.
type: docs
weight: 970
url: /ru/net/aspose.slides/camera/
---
## Camera class

Представляет камеру.

```csharp
public class Camera : PVIObject, ICamera
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Позволяет получить базовый интерфейс IPresentationComponent. Только для чтения[`IPresentationComponent`](../ipresentationcomponent). |
| [CameraType](../../aspose.slides/camera/cameratype) { get; set; } | Тип камеры. Чтение/запись[`CameraPresetType`](../camerapresettype). |
| [FieldOfViewAngle](../../aspose.slides/camera/fieldofviewangle) { get; set; } | FOV камеры (0-180 град, поле зрения). Чтение/записьSingle. |
| [Zoom](../../aspose.slides/camera/zoom) { get; set; } | Увеличение камеры (положительное значение в процентах). Чтение/записьSingle. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Сравнивает с указанным объектом. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Возвращает хэш-код. |
| [GetRotation](../../aspose.slides/camera/getrotation)() | Вращение определяется с помощью координаты широты, координаты долготы и вращения вокруг оси как координаты широты и долготы. первый элемент возвращаемого массива - широта, второй - долгота, третий - оборот. Возвращает null, если вращение не определено. |
| [SetRotation](../../aspose.slides/camera/setrotation)(float, float, float) | Вращение определяется с помощью координаты широты, координаты долготы и вращения вокруг оси как координаты широты и долготы. Если какое-либо из значений координат имеет значение float.NaN, все вращения не определены. |

### Смотрите также

* class [PVIObject](../pviobject)
* interface [ICamera](../icamera)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->