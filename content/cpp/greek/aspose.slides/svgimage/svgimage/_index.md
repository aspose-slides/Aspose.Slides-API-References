---
title: SvgImage()
second_title: Aspose.Slides – Αναφορά API για C++
description: Δημιουργεί νέο αντικείμενο SvgImage.
type: docs
weight: 53
url: /el/aspose.slides/svgimage/svgimage/
---
## SvgImage::SvgImage(System::ArrayPtr\<uint8_t\>) κατασκευαστής


Δημιουργεί ένα νέο [SvgImage](../) αντικείμενο.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::ArrayPtr<uint8_t> data)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Δεδομένα Svg. |

## SvgImage::SvgImage(System::String) κατασκευαστής


Δημιουργεί ένα νέο [SvgImage](../) αντικείμενο.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::String svgContent)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| svgContent | [System::String](../../../system/string/) | Περιεχόμενο Svg. |

## SvgImage::SvgImage(System::SharedPtr\<System::IO::Stream\>) κατασκευαστής


Δημιουργεί ένα νέο [SvgImage](../) αντικείμενο.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::SharedPtr<System::IO::Stream> stream)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ροή Svg. |

## SvgImage::SvgImage(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) κατασκευαστής


Δημιουργεί ένα νέο [SvgImage](../) αντικείμενο.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::ArrayPtr<uint8_t> data, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Δεδομένα Svg. |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Ένα αντικείμενο επανάκλησης που χρησιμοποιείται για την ανάκτηση εξωτερικών αντικειμένων. Εάν αυτή η παράμετρος είναι null, όλα τα εξωτερικά αντικείμενα θα αγνοηθούν. |
| baseUri | [System::String](../../../system/string/) | Βασικό URI του καθορισμένου Svg. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |

## SvgImage::SvgImage(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) κατασκευαστής


Δημιουργεί ένα νέο [SvgImage](../) αντικείμενο.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::String svgContent, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| svgContent | [System::String](../../../system/string/) | Περιεχόμενο Svg. |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Ένα αντικείμενο επανάκλησης που χρησιμοποιείται για την ανάκτηση εξωτερικών αντικειμένων. Εάν αυτή η παράμετρος είναι null, όλα τα εξωτερικά αντικείμενα θα αγνοηθούν. |
| baseUri | [System::String](../../../system/string/) | Βασικό URI του καθορισμένου Svg. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |

## SvgImage::SvgImage(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) κατασκευαστής


Δημιουργεί ένα νέο [SvgImage](../) αντικείμενο.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ροή Svg. |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Ένα αντικείμενο επανάκλησης που χρησιμοποιείται για την ανάκτηση εξωτερικών αντικειμένων. Εάν αυτή η παράμετρος είναι null, όλα τα εξωτερικά αντικείμενα θα αγνοηθούν. |
| baseUri | [System::String](../../../system/string/) | Βασικό URI του καθορισμένου Svg. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SvgImage](../)
* Class [String](../../../system/string/)
* Class [Stream](../../../system.io/stream/)
* Class [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)