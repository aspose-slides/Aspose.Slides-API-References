---
title: SlideUtil class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.util/slideutil/
---
## SlideUtil sınıfı

Sunum içinde şekilleri ve metni aramaya yardımcı olacak yöntemler sunar.

SlideUtil türü aşağıdaki üyeleri gösterir:

## Yöntemler

| Metod | Açıklama |
| :- | :- |
| [`find_shape(pres, alt_text)`](/slides/python-net/tr/aspose.slides.util/slideutil/find_shape/#ipresentation-str) | PPTX sunumunda alternatif metne göre şekil bulur. |
| [`find_shape(slide, alt_text)`](/slides/python-net/tr/aspose.slides.util/slideutil/find_shape/#ibaseslide-str) | PPTX sunumunda bir slaytta alternatif metne göre şekil bulur. |
| [`align_shapes(alignment_type, align_to_slide, slide)`](/slides/python-net/tr/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-ibaseslide) | Slayttaki tüm şekillerin konumunu değiştirir. Şekilleri kenar boşluklarına ya da slayt kenarına hizalar<br/>            ya da birbirlerine göre hizalar. |
| [`align_shapes(alignment_type, align_to_slide, slide, shape_indexes)`](/slides/python-net/tr/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-ibaseslide-listint) | Slayttaki seçili şekillerin konumunu değiştirir. Şekilleri kenar boşluklarına ya da slayt kenarına hizalar<br/>             ya da birbirlerine göre hizalar. |
| [`align_shapes(alignment_type, align_to_slide, group_shape)`](/slides/python-net/tr/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-igroupshape) | Grup şekli içindeki tüm şekillerin konumunu değiştirir. Şekilleri kenar boşluklarına ya da slayt kenarına hizalar<br/>            ya da birbirlerine göre hizalar. |
| [`align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes)`](/slides/python-net/tr/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-igroupshape-listint) | Grup şekli içindeki seçili şekillerin konumunu değiştirir. Şekilleri kenar boşluklarına ya da slayt kenarına hizalar<br/>            ya da birbirlerine göre hizalar. |
| [`find_shapes_by_placeholder_type(slide, placeholder_type)`](/slides/python-net/tr/aspose.slides.util/slideutil/find_shapes_by_placeholder_type/#ibaseslide-placeholdertype) | Belirtilen slaytta verilen yer tutucu tipine uyan tüm şekilleri arar. |
| [`find_and_replace_text(presentation, with_masters, find, replace, format)`](/slides/python-net/tr/aspose.slides.util/slideutil/find_and_replace_text/#ipresentation-bool-str-str-portionformat) | Sunumda metni verilen biçimle bulur ve değiştirir |
| [`get_all_text_boxes(slide)`](/slides/python-net/tr/aspose.slides.util/slideutil/get_all_text_boxes/#ibaseslide) | PPTX sunumunda bir slayttaki tüm metin çerçevelerini döndürür. |
| [`get_text_boxes_contains_text(slide, text, check_placeholder_text)`](/slides/python-net/tr/aspose.slides.util/slideutil/get_text_boxes_contains_text/#ibaseslide-str-bool) | Belirtilen slaytta verilen metni içeren tüm metin çerçevelerini döndürür. |
| [`get_all_text_frames(pres, with_masters)`](/slides/python-net/tr/aspose.slides.util/slideutil/get_all_text_frames/#ipresentation-bool) | PPTX sunumundaki tüm metin çerçevelerini döndürür. |
| [`to_save_format(format)`](/slides/python-net/tr/aspose.slides.util/slideutil/to_save_format/#sourceformat) | Bir kaynak dosya biçimini karşılık gelen [`SaveFormat`](/slides/python-net/tr/aspose.slides.export/saveformat) biçimine dönüştürür. |

### Ayrıca Bakınız
* modül [`aspose.slides.util`](/slides/python-net/tr/aspose.slides.util)
* kütüphane [`Aspose.Slides`](/slides/python-net)