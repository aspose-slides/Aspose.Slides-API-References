---
title: MotionEffect class
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.animation/motioneffect/
---
## MotionEffect třída

Reprezentuje chování efektu pohybu.

**Inheritance:**[`MotionEffect`](/slides/python-net/cs/aspose.slides.animation/motioneffect) → [`Behavior`](/slides/python-net/cs/aspose.slides.animation/behavior)

Typ MotionEffect vystavuje následující členy:

## Konstruktorové

| Konstruktor | Popis |
| :- | :- |
| [`__init__(self)`](/slides/python-net/cs/aspose.slides.animation/motioneffect/__init__/#) | Vytvoří novou instanci. |

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`accumulate`](/slides/python-net/cs/aspose.slides.animation/motioneffect/accumulate/) | Reprezentuje, zda jsou animační chování akumulována.<br/>            Čtení/Zápis [`NullableBool`](/slides/python-net/cs/aspose.slides/nullablebool). |
| [`additive`](/slides/python-net/cs/aspose.slides.animation/motioneffect/additive/) | Reprezentuje, zda je aktuální animační chování kombinováno s dalšími běžícími animacemi.<br/>            Čtení/Zápis [`BehaviorAdditiveType`](/slides/python-net/cs/aspose.slides.animation/behavioradditivetype). |
| [`properties`](/slides/python-net/cs/aspose.slides.animation/motioneffect/properties/) | Reprezentuje vlastnosti chování.<br/>            Pouze pro čtení [`IBehaviorPropertyCollection`](/slides/python-net/cs/aspose.slides.animation/ibehaviorpropertycollection). |
| [`timing`](/slides/python-net/cs/aspose.slides.animation/motioneffect/timing/) | Reprezentuje časové vlastnosti pro chování efektu.<br/>            Čtení/Zápis [`ITiming`](/slides/python-net/cs/aspose.slides.animation/itiming). |
| [`from_address`](/slides/python-net/cs/aspose.slides.animation/motioneffect/from_address/) | Určuje souřadnici x/y, odkud se animace spustí (v procentech). <br/>            Čtení/Zápis [`PointF`](/slides/python-net/cs/aspose.slides/pointf). |
| [`to`](/slides/python-net/cs/aspose.slides.animation/motioneffect/to/) | Určuje cílovou polohu pro animační efekt pohybu (v procentech).<br/>            Čtení/Zápis [`PointF`](/slides/python-net/cs/aspose.slides/pointf). |
| [`by`](/slides/python-net/cs/aspose.slides.animation/motioneffect/by/) | Popisuje relativní hodnotu offsetu pro animaci (v procentech).<br/>            Čtení/Zápis [`PointF`](/slides/python-net/cs/aspose.slides/pointf). |
| [`rotation_center`](/slides/python-net/cs/aspose.slides.animation/motioneffect/rotation_center/) | Popisuje střed rotace používaný k otočení pohybové cesty o úhel X.<br/>            Čtení/Zápis [`PointF`](/slides/python-net/cs/aspose.slides/pointf). |
| [`origin`](/slides/python-net/cs/aspose.slides.animation/motioneffect/origin/) | Určuje, na co je relativní původ pohybové cesty, například na rozložení snímku,<br/>            nebo na nadřazený prvek.<br/>            Čtení/Zápis [`MotionOriginType`](/slides/python-net/cs/aspose.slides.animation/motionorigintype). |
| [`path`](/slides/python-net/cs/aspose.slides.animation/motioneffect/path/) | Určuje primitivní cestu následovanou souřadnicemi pro animaci pohybu.<br/>            Čtení/Zápis [`IMotionPath`](/slides/python-net/cs/aspose.slides.animation/imotionpath). |
| [`path_edit_mode`](/slides/python-net/cs/aspose.slides.animation/motioneffect/path_edit_mode/) | Určuje, jak se pohybová cesta posouvá, když se tvar přesune.<br/>            Čtení/Zápis [`MotionPathEditMode`](/slides/python-net/cs/aspose.slides.animation/motionpatheditmode). |
| [`angle`](/slides/python-net/cs/aspose.slides.animation/motioneffect/angle/) | Popisuje relativní úhel pohybové cesty.<br/>            Čtení/Zápis **float**. |


### Viz také
* třída [`Behavior`](/slides/python-net/cs/aspose.slides.animation/behavior)
* třída [`MotionEffect`](/slides/python-net/cs/aspose.slides.animation/motioneffect)
* modul [`aspose.slides.animation`](/slides/python-net/cs/aspose.slides.animation)
* knihovna [`Aspose.Slides`](/slides/python-net)