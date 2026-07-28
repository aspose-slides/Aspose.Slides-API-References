---
title: SetExternalHyperlinkClick()
second_title: Aspose.Slides C++ API referencia
description: Külső hiperhivatkozás beállítása kattintáskor.
type: docs
weight: 1
url: /hu/aspose.slides/hyperlinkmanager/setexternalhyperlinkclick/
---
## HyperlinkManager::SetExternalHyperlinkClick(System::String) metódus


Külső hiperhivatkozást állít be kattintáskor.

```cpp
System::SharedPtr<IHyperlink> Aspose::Slides::HyperlinkManager::SetExternalHyperlinkClick(System::String url) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| url | [System::String](../../../system/string/) | [Hyperlink](../../hyperlink/) URL. |
## Megjegyzés



Az alábbi mintakód azt mutatja, hogyan lehet szövegdobozt hozzáadni a [Hyperlink](../../hyperlink/) használatával. 
```cpp
auto pptxPresentation = System::MakeObject<Presentation>();
// A prezentáció első diáját kapja meg
auto slide = pptxPresentation->get_Slides()->idx_get(0);

// AutoShape objektumot ad hozzá, a típus Rectangle
auto pptxShape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 150.0f, 150.0f, 50.0f);
// Hozzáfér az AutoShape-hoz társított ITextFrame tulajdonsághoz
pptxShape->AddTextFrame(u"");
auto textFrame = pptxShape->get_TextFrame();
auto portion = textFrame->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0);

// Néhány szöveget ad a kerethez
portion->set_Text(u"Aspose.Slides");

// Beállítja a Hyperlinket a portion szövegéhez
auto hyperlinkManager = portion->get_PortionFormat()->get_HyperlinkManager();
hyperlinkManager->SetExternalHyperlinkClick(u"http://www.aspose.com");

// Elmenti a PPTX prezentációt
pptxPresentation->Save(u"hLinkPPTX_out.pptx", SaveFormat::Pptx);
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IHyperlink](../../ihyperlink/)
* Osztály [String](../../../system/string/)
* Osztály [HyperlinkManager](../)
* Névterület [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)