---
title: Camera class
second_title: Aspose.Slides Python számára .NET-en keresztül API-referencia
description: 
type: docs
url: /hu/aspose.slides/camera/
---
## Camera class

Képviseli a Camera-t.

**Öröklés:**[`Camera`](/slides/python-net/hu/aspose.slides/camera) → [`PVIObject`](/slides/python-net/hu/aspose.slides/pviobject)

A Camera típus a következő tagokkal rendelkezik:

## Properties

| Property | Description |
| :- | :- |
| [`camera_type`](/slides/python-net/hu/aspose.slides/camera/camera_type/) | Kamera típusa.<br/>Olvasás/írás [`CameraPresetType`](/slides/python-net/hu/aspose.slides/camerapresettype). |
| [`field_of_view_angle`](/slides/python-net/hu/aspose.slides/camera/field_of_view_angle/) | Kamera FOV (0-180 deg, field of View).<br/>Olvasás/írás **float**. |
| [`zoom`](/slides/python-net/hu/aspose.slides/camera/zoom/) | Kamera zoom (positive value in percentage).<br/>Olvasás/írás **float**. |
| [`slide`](/slides/python-net/hu/aspose.slides/camera/slide/) |  |
| [`presentation`](/slides/python-net/hu/aspose.slides/camera/presentation/) |  |

## Methods

| Method | Description |
| :- | :- |
| [`set_rotation(self, latitude, longitude, revolution)`](/slides/python-net/hu/aspose.slides/camera/set_rotation/#float-float-float) | A forgást a szélességi koordináta,<br/>hosszúsági koordináta és a tengely körüli revolúció használatával definiálják a szélességi és hosszúsági koordináták szerint.<br/>Ha bármely koordináta értéke float.NaN, a forgás nem definiált. |
| [`get_rotation(self)`](/slides/python-net/hu/aspose.slides/camera/get_rotation/#) | A forgást a szélességi koordináta,<br/>hosszúsági koordináta és a tengely körüli revolúció használatával definiálják a szélességi és hosszúsági koordináták szerint.<br/>az első elem a visszatérő tömbben – latitude, a második – longitude, a harmadik – revolution.<br/>None-t ad vissza, ha nincs definiált forgás. |


### Lásd még
* osztály [`Camera`](/slides/python-net/hu/aspose.slides/camera)
* osztály [`PVIObject`](/slides/python-net/hu/aspose.slides/pviobject)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)