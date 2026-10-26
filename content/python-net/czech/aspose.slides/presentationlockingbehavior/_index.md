---
title: PresentationLockingBehavior enumeration
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/presentationlockingbehavior/
---
## PresentationLockingBehavior enumerace

Reprezentuje chování při zacházení se zdrojem [`IPresentation`](/slides/python-net/cs/aspose.slides/ipresentation) (soubor nebo **io.RawIOBase**) během načítání a práce s instancí [`IPresentation`](/slides/python-net/cs/aspose.slides/ipresentation).

Typ PresentationLockingBehavior obsahuje následující členy:

## Pole

| Pole | Popis |
| :- | :- |
| LOAD_AND_RELEASE | Zdroj bude uzamčen pouze po dobu provádění konstruktoru [`IPresentation`](/slides/python-net/cs/aspose.slides/ipresentation).<br/>Pokud je [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/cs/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) nastaven na false, všechny BLOBy <br/>budou načteny do paměti. V opačném případě mohou být použity jiné prostředky, například dočasné soubory. Toto chování je pomalejší než [`PresentationLockingBehavior.KEEP_LOCKED`](/slides/python-net/cs/aspose.slides/presentationlockingbehavior/KEEP_LOCKED) a pokud je možné předat <br/>vlastnictví zdroje [`IPresentation`](/slides/python-net/cs/aspose.slides/ipresentation), doporučuje se použít [`PresentationLockingBehavior.KEEP_LOCKED`](/slides/python-net/cs/aspose.slides/presentationlockingbehavior/KEEP_LOCKED). |
| KEEP_LOCKED | Zdroj bude uzamčen po celou životnost instance [`IPresentation`](/slides/python-net/cs/aspose.slides/ipresentation), dokud nebude <br/>uvolněn.<br/>[`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/cs/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) musí být nastaven na true pro použití <br/>tohoto chování, jinak bude vyvolána výjimka. Toto chování je doporučeno, je rychlejší a spotřebuje méně paměti než [`PresentationLockingBehavior.LOAD_AND_RELEASE`](/slides/python-net/cs/aspose.slides/presentationlockingbehavior/LOAD_AND_RELEASE). |


### Poznámky

Zdroj je parametr předaný konstruktoru [`IPresentation`](/slides/python-net/cs/aspose.slides/ipresentation). V následujícím příkladu je zdrojem soubor „pres.pptx“:

Pro tento příklad bude zdroj (soubor „pres.pptx“) uzamčen po dobu životnosti instance [`IPresentation`](/slides/python-net/cs/aspose.slides/ipresentation), tj. jiný proces jej nemůže měnit ani mazat.


### Viz také
* třída [`IPresentation`](/slides/python-net/cs/aspose.slides/ipresentation)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)