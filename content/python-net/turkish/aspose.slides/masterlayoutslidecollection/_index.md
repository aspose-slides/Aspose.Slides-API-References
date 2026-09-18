---
title: MasterLayoutSlideCollection class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/masterlayoutslidecollection/
---
## MasterLayoutSlideCollection sınıfı

Tanımlı ana slaytın tüm yerleşim slaytlarını içeren bir koleksiyon temsil eder.
            LayoutSlideCollection sınıfını genişleterek, ana slaytın yerleşim slaytlarının bireysel koleksiyonları bağlamında ekleme/ekleme/kaldırma/kopyalama/yeniden sıralama metodları sağlar.

**Kalıtım:**[`MasterLayoutSlideCollection`](/slides/python-net/tr/aspose.slides/masterlayoutslidecollection) → [`LayoutSlideCollection`](/slides/python-net/tr/aspose.slides/layoutslidecollection)

The MasterLayoutSlideCollection type exposes the following members:

## Dizinleyici

| Ad | Açıklama |
| :- | :- |
| [`[index]`](/slides/python-net/tr/aspose.slides/masterlayoutslidecollection/__getitem__/) |  |

## Metotlar

| Metot | Açıklama |
| :- | :- |
| [`get_by_type(self, type)`](/slides/python-net/tr/aspose.slides/masterlayoutslidecollection/get_by_type/#slidelayouttype) | Belirtilen türdeki ilk yerleşim slaytını döndürür.<br/>            Bulunacak yerleşim slaytı türü.[`LayoutSlide`](/slides/python-net/tr/aspose.slides/layoutslide) belirtilen türde veya hiçbir yerleşim bulunamazsa None. |
| [`remove(self, value)`](/slides/python-net/tr/aspose.slides/masterlayoutslidecollection/remove/#ilayoutslide) | Koleksiyondan bir yerleşimi kaldırır. |
| [`remove_unused(self)`](/slides/python-net/tr/aspose.slides/masterlayoutslidecollection/remove_unused/#) | Kullanılmayan yerleşim slaytlarını kaldırır (HasDependingSlides özelliği false olan yerleşim slaytları). |
| [`add_clone(self, source_layout)`](/slides/python-net/tr/aspose.slides/masterlayoutslidecollection/add_clone/#ilayoutslide) | Belirtilen yerleşim slaytının bir kopyasını koleksiyonun sonuna ekler. |
| [`insert_clone(self, index, source_layout)`](/slides/python-net/tr/aspose.slides/masterlayoutslidecollection/insert_clone/#int-ilayoutslide) | Belirtilen yerleşim slaytının bir kopyasını koleksiyonun belirtilen konumuna ekler. |
| [`add(self, layout_type, layout_name)`](/slides/python-net/tr/aspose.slides/masterlayoutslidecollection/add/#slidelayouttype-str) | Yeni bir yerleşim slaytını koleksiyonun sonuna ekler. |
| [`insert(self, index, layout_type, layout_name)`](/slides/python-net/tr/aspose.slides/masterlayoutslidecollection/insert/#int-slidelayouttype-str) | Yeni bir yerleşim slaytını koleksiyonun belirtilen konumuna ekler. |
| [`remove_at(self, index)`](/slides/python-net/tr/aspose.slides/masterlayoutslidecollection/remove_at/#int) | Koleksiyonun belirtilen indeksindeki öğeyi kaldırır. |
| [`reorder(self, index, layout_slide)`](/slides/python-net/tr/aspose.slides/masterlayoutslidecollection/reorder/#int-ilayoutslide) | Yerleşim slaytını koleksiyondan belirtilen konuma taşır. |

### Ayrıca Bakınız
* sınıf [`LayoutSlideCollection`](/slides/python-net/tr/aspose.slides/layoutslidecollection)
* sınıf [`MasterLayoutSlideCollection`](/slides/python-net/tr/aspose.slides/masterlayoutslidecollection)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)