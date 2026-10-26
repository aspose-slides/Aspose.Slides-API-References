---
title: ICell class
second_title: Aspose.Slides Python için .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/icell/
---
## ICell sınıfı

Bir tablodaki hücreyi temsil eder.

ICell türü aşağıdaki üyeleri ortaya çıkarır:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`offset_x`](/slides/python-net/tr/aspose.slides/icell/offset_x/) | Bir tablonun sol kenarından bir hücrenin sol kenarına olan mesafeyi döndürür.<br/>            Salt okunur **float**. |
| [`offset_y`](/slides/python-net/tr/aspose.slides/icell/offset_y/) | Bir tablonun üst kenarından bir hücrenin üst kenarına olan mesafeyi döndürür.<br/>            Salt okunur **float**. |
| [`first_row_index`](/slides/python-net/tr/aspose.slides/icell/first_row_index/) | Hücre tarafından kapsanan ilk satırın dizinini döndürür.<br/>            Salt okunur **int**. |
| [`first_column_index`](/slides/python-net/tr/aspose.slides/icell/first_column_index/) | Hücre tarafından kapsanan ilk sütunun dizinini döndürür.<br/>            Salt okunur **int**. |
| [`width`](/slides/python-net/tr/aspose.slides/icell/width/) | Hücrenin genişliğini döndürür.<br/>            Salt okunur **float**. |
| [`height`](/slides/python-net/tr/aspose.slides/icell/height/) | Hücrenin yüksekliğini döndürür.<br/>            Salt okunur **float**. |
| [`minimal_height`](/slides/python-net/tr/aspose.slides/icell/minimal_height/) | Bir hücrenin minimum yüksekliğini döndürür.<br/>            Bu, hücre tarafından kapsanan tüm satırların minimum yüksekliklerinin toplamıdır.<br/>            Salt okunur **float**. |
| [`margin_left`](/slides/python-net/tr/aspose.slides/icell/margin_left/) | Bir TextFrame içindeki sol kenar boşluğunu döndürür veya ayarlar.<br/>            Okunur/yazılır **float**. |
| [`margin_right`](/slides/python-net/tr/aspose.slides/icell/margin_right/) | Bir TextFrame içindeki sağ kenar boşluğunu döndürür veya ayarlar.<br/>            Okunur/yazılır **float**. |
| [`margin_top`](/slides/python-net/tr/aspose.slides/icell/margin_top/) | Bir TextFrame içindeki üst kenar boşluğunu döndürür veya ayarlar.<br/>            Okunur/yazılır **float**. |
| [`margin_bottom`](/slides/python-net/tr/aspose.slides/icell/margin_bottom/) | Bir TextFrame içindeki alt kenar boşluğunu döndürür veya ayarlar.<br/>            Okunur/yazılır **float**. |
| [`text_vertical_type`](/slides/python-net/tr/aspose.slides/icell/text_vertical_type/) | Dikey metin tipini döndürür veya ayarlar.<br/>            Okunur/yazılır [`TextVerticalType`](/slides/python-net/tr/aspose.slides/textverticaltype). |
| [`text_anchor_type`](/slides/python-net/tr/aspose.slides/icell/text_anchor_type/) | Metin sabitleme tipini döndürür veya ayarlar.<br/>            Okunur/yazılır [`TextAnchorType`](/slides/python-net/tr/aspose.slides/textanchortype). |
| [`anchor_center`](/slides/python-net/tr/aspose.slides/icell/anchor_center/) | Metin kutusunun hücre içinde ortalanıp ortalanmadığını belirler.<br/>            Okunur/yazılır **bool**. |
| [`first_column`](/slides/python-net/tr/aspose.slides/icell/first_column/) | Hücrenin ilk sütununu alır.<br/>            Salt okunur [`IColumn`](/slides/python-net/tr/aspose.slides/icolumn). |
| [`first_row`](/slides/python-net/tr/aspose.slides/icell/first_row/) | Hücrenin ilk satırını alır.<br/>            Salt okunur [`IRow`](/slides/python-net/tr/aspose.slides/irow). |
| [`col_span`](/slides/python-net/tr/aspose.slides/icell/col_span/) | Mevcut hücrenin kapsayacağı, üst tabloyun tablo ızgarasındaki ızgara sütun sayısını döndürür.<br/>            Bu özellik, hücrelerin tabloda diğer hücrelerin dikey sınırlarını kapsayarak birleşmiş görünmesini sağlar.<br/>            Salt okunur **int**. |
| [`row_span`](/slides/python-net/tr/aspose.slides/icell/row_span/) | Birleştirilmiş bir hücrenin kapsadığı satır sayısını döndürür.<br/>            Bu, diğer hücrelerdeki vMerge özniteliği ile birlikte yatay birleştirmenin başlangıç hücresini belirtmek için kullanılır.<br/>            Salt okunur **int**. |
| [`text_frame`](/slides/python-net/tr/aspose.slides/icell/text_frame/) | Bir hücrenin metin çerçevesini döndürür.<br/>            Salt okunur [`ITextFrame`](/slides/python-net/tr/aspose.slides/itextframe). |
| [`table`](/slides/python-net/tr/aspose.slides/icell/table/) | Bir hücrenin üst Table nesnesini döndürür.<br/>            Salt okunur [`ITable`](/slides/python-net/tr/aspose.slides/itable). |
| [`is_merged_cell`](/slides/python-net/tr/aspose.slides/icell/is_merged_cell/) | Hücre herhangi bir ayarlanmış hücreyle birleştirilmişse doğru, aksi takdirde yanlış döndürür.<br/>            Salt okunur **bool**. |
| [`cell_format`](/slides/python-net/tr/aspose.slides/icell/cell_format/) | Bu hücre için biçimlendirme özelliklerini içeren CellFormat nesnesini döndürür.<br/>            Salt okunur [`ICellFormat`](/slides/python-net/tr/aspose.slides/icellformat). |
| [`slide`](/slides/python-net/tr/aspose.slides/icell/slide/) |  |
| [`presentation`](/slides/python-net/tr/aspose.slides/icell/presentation/) |  |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`split_by_col_span(self, index)`](/slides/python-net/tr/aspose.slides/icell/split_by_col_span/#int) | Hücreyi sütun indeksine göre iki hücreye ayırır. |
| [`split_by_row_span(self, index)`](/slides/python-net/tr/aspose.slides/icell/split_by_row_span/#int) | Hücreyi satır indeksine göre iki hücreye ayırır. |
| [`split_by_height(self, height)`](/slides/python-net/tr/aspose.slides/icell/split_by_height/#float) | Hücreyi yüksekliğe göre ayırır. |
| [`split_by_width(self, width)`](/slides/python-net/tr/aspose.slides/icell/split_by_width/#float) | Hücreyi genişliğe göre ayırır. |

### Ayrıca Bakınız
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)