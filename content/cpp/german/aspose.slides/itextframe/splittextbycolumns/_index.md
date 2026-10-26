---
title: SplitTextByColumns()
second_title: Aspose.Slides für C++ API-Referenz
description: Teilt den Textinhalt des ITextFrame in ein Array von Zeichenketten, wobei jedes Element einer separaten Textspalte im Rahmen entspricht.
type: docs
weight: 118
url: /de/aspose.slides/itextframe/splittextbycolumns/
---
## ITextFrame::SplitTextByColumns() Methode

Teilt den Textinhalt des [ITextFrame](../) in ein Array von Zeichenketten, 

 wobei jedes Element einer separaten Textspalte im Rahmen entspricht.

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::ITextFrame::SplitTextByColumns()=0
```

### Rückgabewert

Ein Array von Zeichenketten, wobei jede Zeichenkette den Textinhalt einer bestimmten Spalte im [ITextFrame](../) darstellt.

## Anmerkungen

Wenn der Textrahmen nicht mehrere Spalten enthält, hat das zurückgegebene Array ein einzelnes Element, das den vollständigen Text enthält. 

Leere Spalten werden im Array als leere Zeichenketten dargestellt. 

Das folgende Beispiel zeigt, wie [ITextFrame::SplitTextByColumns](./) verwendet wird: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"example.pptx");

// Erhalte die erste Form auf der Folie und cast sie zu ITextFrame
System::SharedPtr<ITextFrame> textFrame = System::AsCast<ITextFrame>(pres->get_Slide(0)->get_Shape(0));
// Teile den Textrahmeninhalt in Spalten auf
System::ArrayPtr<System::String> columnsText = textFrame->SplitTextByColumns();
// Gibt den Text jeder Spalte in der Konsole aus
for (System::String column : columnsText)
{
    System::Console::WriteLine(column);
}
```

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [ITextFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)