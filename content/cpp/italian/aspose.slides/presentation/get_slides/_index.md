---
title: get_Slides()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce un elenco di tutte le diapositive definite nella presentazione. Solo lettura ISlideCollection.
type: docs
weight: 53
url: /it/aspose.slides/presentation/get_slides/
---
## Presentation::get_Slides() metodo


Restituisce un elenco di tutte le diapositive definite nella presentazione. Solo lettura [ISlideCollection](../../islidecollection/).

```cpp
System::SharedPtr<ISlideCollection> Aspose::Slides::Presentation::get_Slides() override
```

## Osservazioni


Il seguente esempio mostra come impostare il colore di sfondo delle diapositive di PowerPoint [Presentation](../). 
```cpp
// Istanzia la classe Presentation che rappresenta il file della presentazione
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

// Imposta il colore di sfondo del primo ISlide a Blu
slide->get_Background()->set_Type(BackgroundType::OwnBackground);
slide->get_Background()->get_FillFormat()->set_FillType(FillType::Solid);
slide->get_Background()->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Blue());
pres->Save(u"ContentBG_out.pptx", SaveFormat::Pptx);
```
 Il seguente esempio mostra come impostare l'immagine di sfondo delle diapositive di PowerPoint [Presentation](../). 
```cpp
// Istanzia la classe Presentation che rappresenta il file della presentazione
auto pres = System::MakeObject<Presentation>(u"SetImageAsBackground.pptx");
auto slide = pres->get_Slides()->idx_get(0);

// Imposta lo sfondo con un'immagine
slide->get_Background()->set_Type(BackgroundType::OwnBackground);
slide->get_Background()->get_FillFormat()->set_FillType(FillType::Picture);
slide->get_Background()->get_FillFormat()->get_PictureFillFormat()->set_PictureFillMode(PictureFillMode::Stretch);
// Imposta l'immagine
auto img = System::ExplicitCast<System::Drawing::Image>(System::MakeObject<System::Drawing::Bitmap>(dataDir + u"Tulips.jpg"));
// Aggiunge l'immagine alla collezione delle immagini della presentazione
auto imgx = pres->get_Images()->AddImage(img);
slide->get_Background()->get_FillFormat()->get_PictureFillFormat()->get_Picture()->set_Image(imgx);
// Scrive la presentazione su disco
pres->Save(u"ContentBG_Img_out.pptx", SaveFormat::Pptx);
```
 Il seguente esempio mostra come aggiungere la transizione della diapositiva [Presentation](../). 
```cpp
// Istanzia la classe Presentation per caricare il file della presentazione sorgente
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");

// Applica la transizione di tipo cerchio sulla diapositiva 1
presentation->get_Slides()->idx_get(0)->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Circle);
// Applica la transizione di tipo comb sulla diapositiva 2
presentation->get_Slides()->idx_get(1)->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Comb);
// Scrivi la presentazione su disco
presentation->Save(u"SampleTransition_out.pptx", SaveFormat::Pptx);
```
 Il seguente esempio mostra come aggiungere una transizione avanzata della diapositiva. 
```cpp
// Istanzia la classe Presentation che rappresenta un file di presentazione
auto pres = System::MakeObject<Presentation>(u"BetterSlideTransitions.pptx");

auto slide1 = pres->get_Slides()->idx_get(0);
auto slide2 = pres->get_Slides()->idx_get(1);
auto slide3 = pres->get_Slides()->idx_get(2);

// Applica la transizione di tipo cerchio sulla diapositiva 1
slide1->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Circle);
// Imposta il tempo di transizione a 3 secondi
slide1->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide1->get_SlideShowTransition()->set_AdvanceAfterTime(3000);
// Applica la transizione di tipo comb sulla diapositiva 2
slide2->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Comb);
// Imposta il tempo di transizione a 5 secondi
slide2->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide2->get_SlideShowTransition()->set_AdvanceAfterTime(5000);
// Applica la transizione di tipo zoom sulla diapositiva 3
slide3->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Zoom);
// Imposta il tempo di transizione a 7 secondi
slide3->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide3->get_SlideShowTransition()->set_AdvanceAfterTime(7000);
// Scrivi la presentazione su disco
pres->Save(u"SampleTransition_out.pptx", SaveFormat::Pptx);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISlideCollection](../../islidecollection/)
* Classe [Presentation](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)