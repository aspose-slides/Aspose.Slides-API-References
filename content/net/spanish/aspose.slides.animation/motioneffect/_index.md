---
title: MotionEffect
second_title: Referencia de API de Aspose.Slides para .NET
description: Representa el comportamiento del efecto de movimiento.
type: docs
weight: 590
url: /es/aspose.slides.animation/motioneffect/
---

## Clase MotionEffect

Representa el comportamiento del efecto de movimiento.

```csharp
public class MotionEffect : Behavior, IMotionEffect
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [MotionEffect](motioneffect)() | El constructor por defecto. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Accumulate](../../aspose.slides.animation/behavior/accumulate) { get; set; } | Representa si los comportamientos de animación se acumulan. Lectura/escritura [`NullableBool`](../../aspose.slides/nullablebool). |
| [Additive](../../aspose.slides.animation/behavior/additive) { get; set; } | Representa si el comportamiento de animación actual se combina con otras animaciones en ejecución. Lectura/escritura [`BehaviorAdditiveType`](../behavioradditivetype). |
| [Angle](../../aspose.slides.animation/motioneffect/angle) { get; set; } | Describe el ángulo relativo de la trayectoria de movimiento. Lectura/escritura Single. |
| [By](../../aspose.slides.animation/motioneffect/by) { get; set; } | Describe el valor de desplazamiento relativo para la animación (en porcentajes). Lectura/escritura PointF. |
| [From](../../aspose.slides.animation/motioneffect/from) { get; set; } | Especifica una coordenada x/y desde la cual comenzar la animación (en porcentajes). Lectura/escritura PointF. |
| [Origin](../../aspose.slides.animation/motioneffect/origin) { get; set; } | Especifica cuál es el origen de la trayectoria de movimiento en relación con el diseño de la diapositiva, o el padre. Lectura/escritura [`MotionOriginType`](../motionorigintype). |
| [Path](../../aspose.slides.animation/motioneffect/path) { get; set; } | Especifica el primitivo de la trayectoria seguido por las coordenadas para el movimiento de la animación. Lectura/escritura [`IMotionPath`](../imotionpath). |
| [PathEditMode](../../aspose.slides.animation/motioneffect/patheditmode) { get; set; } | Especifica cómo se mueve la trayectoria de movimiento cuando la forma se mueve. Lectura/escritura [`MotionPathEditMode`](../motionpatheditmode). |
| [Properties](../../aspose.slides.animation/behavior/properties) { get; } | Representa las propiedades del comportamiento. Solo lectura [`IBehaviorPropertyCollection`](../ibehaviorpropertycollection). |
| [RotationCenter](../../aspose.slides.animation/motioneffect/rotationcenter) { get; set; } | Describe el centro de rotación utilizado para rotar una trayectoria de movimiento por un ángulo X. Lectura/escritura PointF. |
| [Timing](../../aspose.slides.animation/behavior/timing) { get; set; } | Representa las propiedades de tiempo para el comportamiento del efecto. Lectura/escritura [`ITiming`](../itiming). |
| [To](../../aspose.slides.animation/motioneffect/to) { get; set; } | Especifica la ubicación objetivo para un efecto de movimiento de animación (en porcentajes). Lectura/escritura PointF. |

### Véase también

* clase [Behavior](../behavior)
* interfaz [IMotionEffect](../imotioneffect)
* espacio de nombres [Aspose.Slides.Animation](../../aspose.slides.animation)
* ensamblado [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->