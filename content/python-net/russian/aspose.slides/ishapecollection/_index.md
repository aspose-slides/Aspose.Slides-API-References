---
title: IShapeCollection class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/ishapecollection/
---
## IShapeCollection класс

Представляет коллекцию фигур.

Тип IShapeCollection предоставляет следующие члены:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`parent_group`](/slides/python-net/ru/aspose.slides/ishapecollection/parent_group/) | Получает объект родительской группы фигур для коллекции фигур.<br/>            Только для чтения [`IGroupShape`](/slides/python-net/ru/aspose.slides/igroupshape). |

Получает элемент по указанному индексу.
            Только для чтения [`IShape`](/slides/python-net/ru/aspose.slides/ishape).

## Индексатор

| Имя | Описание |
| :- | :- |
| [`[index]`](/slides/python-net/ru/aspose.slides/ishapecollection/__getitem__/) |  |

## Методы

| Метод | Описание |
| :- | :- |
| [`add_chart(self, type, x, y, width, height)`](/slides/python-net/ru/aspose.slides/ishapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float) | Создаёт новую диаграмму, инициализирует её данными образцовых рядов и настройками, и добавляет<br/>            её в конец коллекции фигур. |
| [`add_chart(self, type, x, y, width, height, init_with_sample)`](/slides/python-net/ru/aspose.slides/ishapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float-bool) | Создаёт новую диаграмму, инициализирует её данными образцовых рядов и настройками, и добавляет<br/>            её в конец коллекции фигур. |
| [`insert_chart(self, type, x, y, width, height, index)`](/slides/python-net/ru/aspose.slides/ishapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int) | Создаёт новую диаграмму, инициализирует её данными образцовых рядов и настройками,<br/>            и вставляет её в коллекцию фигур по указанному индексу. |
| [`insert_chart(self, type, x, y, width, height, index, init_with_sample)`](/slides/python-net/ru/aspose.slides/ishapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int-bool) | Создаёт новую диаграмму, инициализирует её данными образцовых рядов и настройками,<br/>            и вставляет её в коллекцию фигур по указанному индексу. |
| [`add_ole_object_frame(self, x, y, width, height, data_info)`](/slides/python-net/ru/aspose.slides/ishapecollection/add_ole_object_frame/#float-float-float-float-ioleembeddeddatainfo) | Создаёт новый кадр OLE-объекта и добавляет его в конец коллекции фигур. |
| [`add_ole_object_frame(self, x, y, width, height, class_name, path)`](/slides/python-net/ru/aspose.slides/ishapecollection/add_ole_object_frame/#float-float-float-float-str-str) | Создаёт новый кадр OLE-объекта и добавляет его в конец коллекции фигур. |
| [`insert_ole_object_frame(self, index, x, y, width, height, data_info)`](/slides/python-net/ru/aspose.slides/ishapecollection/insert_ole_object_frame/#int-float-float-float-float-ioleembeddeddatainfo) | Создаёт новый кадр OLE-объекта и вставляет его в коллекцию фигур по указанному индексу. |
| [`insert_ole_object_frame(self, index, x, y, width, height, class_name, path)`](/slides/python-net/ru/aspose.slides/ishapecollection/insert_ole_object_frame/#int-float-float-float-float-str-str) | Создаёт новый кадр OLE-объекта и вставляет его в коллекцию фигур по указанному индексу. |
| [`add_zoom_frame(self, x, y, width, height, slide)`](/slides/python-net/ru/aspose.slides/ishapecollection/add_zoom_frame/#float-float-float-float-islide) | Создаёт новый кадр Zoom и добавляет его в конец коллекции фигур. |
| [`add_zoom_frame(self, x, y, width, height, slide, image)`](/slides/python-net/ru/aspose.slides/ishapecollection/add_zoom_frame/#float-float-float-float-islide-ippimage) | Создаёт новый кадр Zoom и добавляет его в конец коллекции фигур. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide)`](/slides/python-net/ru/aspose.slides/ishapecollection/insert_zoom_frame/#int-float-float-float-float-islide) | Создаёт новый кадр Zoom и вставляет его в коллекцию фигур по указанному индексу. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide, image)`](/slides/python-net/ru/aspose.slides/ishapecollection/insert_zoom_frame/#int-float-float-float-float-islide-ippimage) | Создаёт новый кадр Zoom с предопределённым изображением и вставляет его в коллекцию фигур<br/>            по указанному индексу. |
| [`add_section_zoom_frame(self, x, y, width, height, section)`](/slides/python-net/ru/aspose.slides/ishapecollection/add_section_zoom_frame/#float-float-float-float-isection) | Создаёт новый кадр Section Zoom и добавляет его в конец коллекции фигур. |
| [`add_section_zoom_frame(self, x, y, width, height, section, image)`](/slides/python-net/ru/aspose.slides/ishapecollection/add_section_zoom_frame/#float-float-float-float-isection-ippimage) | Создаёт новый кадр Section Zoom с предопределённым изображением и добавляет его в конец коллекции<br/>            фигур. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section)`](/slides/python-net/ru/aspose.slides/ishapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection) | Создаёт новый кадр Section Zoom и вставляет его в коллекцию фигур по указанному индексу. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section, image)`](/slides/python-net/ru/aspose.slides/ishapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection-ippimage) | Создаёт новый кадр Section Zoom с предопределённым изображением и вставляет его в коллекцию фигур<br/>            по указанному индексу. |
| [`add_video_frame(self, x, y, width, height, fname)`](/slides/python-net/ru/aspose.slides/ishapecollection/add_video_frame/#float-float-float-float-str) | Создаёт новый видеокадр и добавляет его в конец коллекции фигур. |
| [`add_video_frame(self, x, y, width, height, video)`](/slides/python-net/ru/aspose.slides/ishapecollection/add_video_frame/#float-float-float-float-ivideo) | Создаёт новый видеокадр и добавляет его в конец коллекции фигур. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio_stream)`](/slides/python-net/ru/aspose.slides/ishapecollection/add_audio_frame_embedded/#float-float-float-float-iorawiobase) | Создаёт новый аудиокадр со вложенным WAV-файлом и добавляет его в конец коллекции фигур.<br/>            Встроенный аудио-файл добавляется в коллекцию Presentation.Audios. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio)`](/slides/python-net/ru/aspose.slides/ishapecollection/add_audio_frame_embedded/#float-float-float-float-iaudio) | Создаёт новый аудиокадр и добавляет его в конец коллекции фигур, используя существующий объект аудио из списка Presentation.Audios. |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream)`](/slides/python-net/ru/aspose.slides/ishapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iorawiobase) | Создаёт новый аудиокадр со вложенным WAV-файлом и вставляет его в коллекцию фигур по указанному индексу. Встроенный аудио-файл добавляется в коллекцию Presentation.Audios.<br/>            |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio)`](/slides/python-net/ru/aspose.slides/ishapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iaudio) | Создаёт новый аудиокадр и вставляет его в коллекцию фигур по указанному индексу, используя существующий объект аудио из списка Presentation.Audios. |
| [`to_array(self)`](/slides/python-net/ru/aspose.slides/ishapecollection/to_array/#) | Создаёт и возвращает массив, содержащий все фигуры. |
| [`to_array(self, start_index, count)`](/slides/python-net/ru/aspose.slides/ishapecollection/to_array/#int-int) | Создаёт и возвращает массив, содержащий все фигуры в указанном диапазоне. |
| [`reorder(self, index, shape)`](/slides/python-net/ru/aspose.slides/ishapecollection/reorder/#int-ishape) | Перемещает указанную фигуру в новое положение внутри коллекции фигур. |
| [`reorder(self, index, shapes)`](/slides/python-net/ru/aspose.slides/ishapecollection/reorder/#int-listishape) | Перемещает указанные фигуры внутри коллекции фигур, размещая их, начиная с заданного индекса. |
| [`add_auto_shape(self, shape_type, x, y, width, height)`](/slides/python-net/ru/aspose.slides/ishapecollection/add_auto_shape/#shapetype-float-float-float-float) | Создаёт новую автофигуру с форматом по умолчанию и добавляет её в конец коллекции фигур.<br/>            |
| [`add_auto_shape(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/ru/aspose.slides/ishapecollection/add_auto_shape/#shapetype-float-float-float-float-bool) | Создаёт новую автофигуру и добавляет её в конец коллекции фигур, опционально инициализируя её форматированием шаблона по умолчанию. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height)`](/slides/python-net/ru/aspose.slides/ishapecollection/insert_auto_shape/#int-shapetype-float-float-float-float) | Создаёт новую автофигуру и вставляет её в коллекцию фигур по указанному индексу,<br/>            применяя формат шаблона по умолчанию. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/ru/aspose.slides/ishapecollection/insert_auto_shape/#int-shapetype-float-float-float-float-bool) | Создаёт новую автофигуру и вставляет её в коллекцию фигур по указанному индексу,<br/>            опционально инициализируя её стилизацией шаблона по умолчанию. |
| [`add_group_shape(self)`](/slides/python-net/ru/aspose.slides/ishapecollection/add_group_shape/#) | Создаёт новую пустую групповую фигуру и добавляет её в конец коллекции фигур.<br/>            Кадр группы будет автоматически подгоняться под любые добавляемые в неё фигуры. |
| [`add_group_shape(self, svg_image, x, y, width, height)`](/slides/python-net/ru/aspose.slides/ishapecollection/add_group_shape/#isvgimage-float-float-float-float) | Создаёт новую групповую фигуру, преобразует указанное SVG-изображение в отдельные фигуры,<br/>            и добавляет получившуюся группу в конец коллекции фигур. |
| [`add_connector(self, shape_type, x, y, width, height)`](/slides/python-net/ru/aspose.slides/ishapecollection/add_connector/#shapetype-float-float-float-float) | Создаёт новую соединительную фигуру с оформлением шаблона по умолчанию и добавляет её в конец коллекции фигур.<br/>            |
| [`add_connector(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/ru/aspose.slides/ishapecollection/add_connector/#shapetype-float-float-float-float-bool) | Создаёт новую соединительную фигуру и добавляет её в конец коллекции фигур,<br/>            опционально применяя оформление шаблона по умолчанию. |
| [`insert_connector(self, index, shape_type, x, y, width, height)`](/slides/python-net/ru/aspose.slides/ishapecollection/insert_connector/#int-shapetype-float-float-float-float) | Создаёт новую соединительную фигуру и вставляет её в коллекцию фигур по указанному индексу,<br/>            применяя оформление шаблона по умолчанию. |
| [`insert_connector(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/ru/aspose.slides/ishapecollection/insert_connector/#int-shapetype-float-float-float-float-bool) | Создаёт новую соединительную фигуру и вставляет её в коллекцию фигур по указанному индексу,<br/>            опционально применяя оформление шаблона по умолчанию. |
| [`add_clone(self, source_shape, x, y, width, height)`](/slides/python-net/ru/aspose.slides/ishapecollection/add_clone/#ishape-float-float-float-float) | Создаёт копию указанной фигуры и добавляет её в конец коллекции фигур. |
| [`add_clone(self, source_shape, x, y)`](/slides/python-net/ru/aspose.slides/ishapecollection/add_clone/#ishape-float-float) | Создаёт копию указанной фигуры и добавляет её в конец коллекции фигур.<br/>            Новая фигура сохраняет ширину и высоту `source_shape`. |
| [`add_clone(self, source_shape)`](/slides/python-net/ru/aspose.slides/ishapecollection/add_clone/#ishape) | Создаёт копию указанной фигуры и добавляет её в конец коллекции фигур.<br/>            Клонированная фигура сохраняет позицию и размер оригинала. |
| [`insert_clone(self, index, source_shape, x, y, width, height)`](/slides/python-net/ru/aspose.slides/ishapecollection/insert_clone/#int-ishape-float-float-float-float) | Создаёт копию указанной фигуры и вставляет её в коллекцию фигур по указанному индексу. |
| [`insert_clone(self, index, source_shape, x, y)`](/slides/python-net/ru/aspose.slides/ishapecollection/insert_clone/#int-ishape-float-float) | Создаёт копию указанной фигуры и вставляет её в коллекцию фигур по указанному индексу.<br/>            Новая фигура сохраняет ширину и высоту `source_shape`. |
| [`insert_clone(self, index, source_shape)`](/slides/python-net/ru/aspose.slides/ishapecollection/insert_clone/#int-ishape) | Создаёт копию указанной фигуры и вставляет её в коллекцию фигур по указанному индексу.<br/>            Клонированная фигура сохраняет позицию и размер оригинала. |
| [`add_smart_art(self, x, y, width, height, layout_type)`](/slides/python-net/ru/aspose.slides/ishapecollection/add_smart_art/#float-float-float-float-asposeslidessmartartsmartartlayouttype) | Создаёт диаграмму SmartArt и добавляет её в конец коллекции фигур. |
| [`add_summary_zoom_frame(self, x, y, width, height)`](/slides/python-net/ru/aspose.slides/ishapecollection/add_summary_zoom_frame/#float-float-float-float) | Создаёт новый кадр Summary Zoom и добавляет его в конец коллекции фигур. |
| [`insert_summary_zoom_frame(self, index, x, y, width, height)`](/slides/python-net/ru/aspose.slides/ishapecollection/insert_summary_zoom_frame/#int-float-float-float-float) | Создаёт новый кадр Summary Zoom и вставляет его в коллекцию фигур по указанному индексу. |
| [`insert_video_frame(self, index, x, y, width, height, fname)`](/slides/python-net/ru/aspose.slides/ishapecollection/insert_video_frame/#int-float-float-float-float-str) | Создаёт новый видеокадр и вставляет его в коллекцию фигур по указанному индексу. |
| [`add_audio_frame_cd(self, x, y, width, height)`](/slides/python-net/ru/aspose.slides/ishapecollection/add_audio_frame_cd/#float-float-float-float) | Создаёт новый аудиокадр, связанный с CD-треком, и добавляет его в конец коллекции фигур. |
| [`insert_audio_frame_cd(self, index, x, y, width, height)`](/slides/python-net/ru/aspose.slides/ishapecollection/insert_audio_frame_cd/#int-float-float-float-float) | Создаёт новый аудиокадр, связанный с CD-треком, и вставляет его в коллекцию фигур<br/>            по указанному индексу. |
| [`add_audio_frame_linked(self, x, y, width, height, fname)`](/slides/python-net/ru/aspose.slides/ishapecollection/add_audio_frame_linked/#float-float-float-float-str) | Создаёт новый аудиокадр, связанный с внешним аудиофайлом, и добавляет его в конец<br/>            коллекции фигур. |
| [`insert_audio_frame_linked(self, index, x, y, width, height, fname)`](/slides/python-net/ru/aspose.slides/ishapecollection/insert_audio_frame_linked/#int-float-float-float-float-str) | Создаёт новый аудиокадр, связанный с внешним аудиофайлом, и вставляет его в коллекцию фигур<br/>            по указанному индексу. |
| [`index_of(self, shape)`](/slides/python-net/ru/aspose.slides/ishapecollection/index_of/#ishape) | Возвращает нулевой индекс первого вхождения указанной фигуры в коллекцию. |
| [`add_math_shape(self, x, y, width, height)`](/slides/python-net/ru/aspose.slides/ishapecollection/add_math_shape/#float-float-float-float) | Создаёт новую прямоугольную автофигуру для размещения математического содержимого и добавляет её в\n            конец коллекции фигур. |
| [`insert_group_shape(self, index)`](/slides/python-net/ru/aspose.slides/ishapecollection/insert_group_shape/#int) | Создаёт новую пустую групповую фигуру и вставляет её в коллекцию фигур по указанному индексу.<br/>            Кадр группы будет автоматически подгоняться под любые добавляемые в неё фигуры. |
| [`add_picture_frame(self, shape_type, x, y, width, height, image)`](/slides/python-net/ru/aspose.slides/ishapecollection/add_picture_frame/#shapetype-float-float-float-float-ippimage) | Создаёт новый кадр изображения, содержащий указанное изображение, и добавляет его в конец коллекции фигур. |
| [`insert_picture_frame(self, index, shape_type, x, y, width, height, image)`](/slides/python-net/ru/aspose.slides/ishapecollection/insert_picture_frame/#int-shapetype-float-float-float-float-ippimage) | Создаёт новый кадр изображения, содержащий указанное изображение, и вставляет его в коллекцию фигур\n            по указанному индексу. |
| [`add_table(self, x, y, column_widths, row_heights)`](/slides/python-net/ru/aspose.slides/ishapecollection/add_table/#float-float-listfloat-listfloat) | Создаёт новую таблицу и добавляет её в конец коллекции фигур. |
| [`insert_table(self, index, x, y, column_widths, row_heights)`](/slides/python-net/ru/aspose.slides/ishapecollection/insert_table/#int-float-float-listfloat-listfloat) | Создаёт новую таблицу и вставляет её в коллекцию фигур по указанному индексу. |
| [`remove_at(self, index)`](/slides/python-net/ru/aspose.slides/ishapecollection/remove_at/#int) | Удаляет фигуру по указанному индексу из коллекции фигур. |
| [`remove(self, shape)`](/slides/python-net/ru/aspose.slides/ishapecollection/remove/#ishape) | Удаляет первое вхождение указанной фигуры из коллекции фигур. |
| [`clear(self)`](/slides/python-net/ru/aspose.slides/ishapecollection/clear/#) | Удаляет все фигуры из коллекции фигур. |


### См. также
* класс [`IShape`](/slides/python-net/ru/aspose.slides/ishape)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)