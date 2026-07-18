---
title: ForEach
second_title: Aspose.Slides για C++ API Αναφορά
description: Αντιπροσωπεύει μια ομάδα μεθόδων που προορίζονται να επαναλαμβάνονται πάνω σε διαφορετικά αντικείμενα μοντέλου Presentation. Αυτές οι μέθοδοι μπορούν να είναι χρήσιμες εάν χρειάζεται να επαναλάβετε και να αλλάξετε τη μορφοποίηση ή το περιεχόμενο ορισμένων στοιχείων του Presentation, π.χ. να αλλάξετε τη μορφοποίηση κάθε τμήματος.
type: docs
weight: 40
url: /el/aspose.slides.lowcode/foreach/
---
## ForEach κλάση

Αντιπροσωπεύει μια ομάδα μεθόδων που προορίζονται να επαναλαμβάνονται πάνω σε διαφορετικά [Presentation](../../aspose.slides/presentation/) μοντέλο αντικειμένων. Αυτές οι μέθοδοι μπορούν να είναι χρήσιμες εάν χρειάζεται να επαναλάβετε και να αλλάξετε τη μορφοποίηση ή το περιεχόμενο ορισμένων στοιχείων του [Presentation](../../aspose.slides/presentation/), π.χ. να αλλάξετε τη μορφοποίηση κάθε τμήματος.

```cpp
class ForEach
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  [ForEach](./foreach/)() |  |
| static void [LayoutSlide](./layoutslide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachLayoutSlideCallback](./foreachlayoutslidecallback/)) | Επαναλάβετε κάθε [ForEach::LayoutSlide](./layoutslide/) στο [Presentation](../../aspose.slides/presentation/). |
| static void [MasterSlide](./masterslide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachMasterSlideCallback](./foreachmasterslidecallback/)) | Επαναλάβετε κάθε [ForEach::MasterSlide](./masterslide/) στο [Presentation](../../aspose.slides/presentation/). |
| static void [Paragraph](./paragraph/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachParagraphCallback](./foreachparagraphcallback/)) | Επαναλάβετε κάθε [ForEach::Paragraph](./paragraph/) στο [Presentation](../../aspose.slides/presentation/). |
| static void [Paragraph](./paragraph/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachParagraphCallback](./foreachparagraphcallback/)) | Επαναλάβετε κάθε [ForEach::Paragraph](./paragraph/) στο [Presentation](../../aspose.slides/presentation/). |
| static void [Portion](./portion/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachPortionCallback](./foreachportioncallback/)) | Επαναλάβετε κάθε [ForEach::Portion](./portion/) στο [Presentation](../../aspose.slides/presentation/). |
| static void [Portion](./portion/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachPortionCallback](./foreachportioncallback/)) | Επαναλάβετε κάθε [ForEach::Portion](./portion/) στο [Presentation](../../aspose.slides/presentation/). |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | Επαναλάβετε κάθε [ForEach::Shape](./shape/) στο [Presentation](../../aspose.slides/presentation/). |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | Επαναλάβετε κάθε [ForEach::Shape](./shape/) στο [Presentation](../../aspose.slides/presentation/). |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[BaseSlide](../../aspose.slides/baseslide/)\>, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | Επαναλάβετε κάθε [ForEach::Shape](./shape/) στο [BaseSlide](../../aspose.slides/baseslide/). |
| static void [Slide](./slide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachSlideCallback](./foreachslidecallback/)) | Επαναλάβετε κάθε [ForEach::Slide](./slide/) στο [Presentation](../../aspose.slides/presentation/). |

## Τύποι ορισμού

| Τύπος ορισμού | Περιγραφή |
| --- | --- |
| [ForEachSlideCallback](./foreachslidecallback/) | Αντίκληση που θα κληθεί για κάθε [ForEach::Slide](./slide/) στο [Presentation](../../aspose.slides/presentation/). |
| [ForEachMasterSlideCallback](./foreachmasterslidecallback/) | Αντίκληση που θα κληθεί για κάθε [ForEach::MasterSlide](./masterslide/) στο [Presentation](../../aspose.slides/presentation/). |
| [ForEachLayoutSlideCallback](./foreachlayoutslidecallback/) | Αντίκληση που θα κληθεί για κάθε [ForEach::LayoutSlide](./layoutslide/) στο [Presentation](../../aspose.slides/presentation/). |
| [ForEachShapeCallback](./foreachshapecallback/) | Αντίκληση που θα κληθεί για κάθε [ForEach::Shape](./shape/) στο [Presentation](../../aspose.slides/presentation/). |
| [ForEachParagraphCallback](./foreachparagraphcallback/) | Αντίκληση που θα κληθεί για κάθε [ForEach::Paragraph](./paragraph/) στο [BaseSlide](../../aspose.slides/baseslide/). |
| [ForEachPortionCallback](./foreachportioncallback/) | Αντίκληση που θα κληθεί για κάθε [ForEach::Portion](./portion/) στο [ForEach::Paragraph](./paragraph/) στο [BaseSlide](../../aspose.slides/baseslide/). |

## Παρατηρήσεις

```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index) -> void
{
    portion->get_PortionFormat()->set_LatinFont(System::MakeObject<FontData>(u"Times New Roman"));
};
auto callback = std::function<void(SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Portion(presentation, callback);

presentation->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Χώρος ονοματών [Aspose::Slides::LowCode](../)
* Βιβλιοθήκη [Aspose.Slides](../../)