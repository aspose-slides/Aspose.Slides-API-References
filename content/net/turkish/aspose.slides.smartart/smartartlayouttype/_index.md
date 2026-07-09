---
title: SmartArtLayoutType
second_title: Aspose.Sildes for .NET API Referansı
description: Bir SmartArt diyagramının düzen türünü temsil eder.
type: docs
weight: 10620
url: /tr/aspose.slides.smartart/smartartlayouttype/
---
## SmartArtLayoutType numaralandırması

Bir SmartArt diyagramının düzen türünü temsil eder.

```csharp
public enum SmartArtLayoutType
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| AccentProcess | `0` | Bir görev, süreç veya iş akışında ilerlemeyi, zaman çizelgesini veya sıralı adımları göstermek için kullanılır. Hem Seviye 1 hem de Seviye 2 metinlerini göstermek için iyidir. |
| AccentedPicture | `1` | Merkezi, fotoğrafik bir fikri yan taraftaki ilgili fikirlerle göstermek için kullanılır. En üst Seviye 1 metni merkezi resim üzerindedir. Diğer Seviye 1 şekillerinin karşılık gelen metni küçük dairesel resimlerin yanındadır. Bu düzen, metin olmadığında da iyi çalışır. |
| AlternatingFlow | `2` | Bir görev, süreç veya iş akışında bilgi gruplarını veya sıralı adımları göstermek için kullanılır. Bilgi grupları arasındaki etkileşim veya ilişkileri vurgular. |
| AlternatingHexagons | `3` | Birbiriyle bağlantılı fikirlerin bir serisini temsil etmek için kullanılır. Seviye 1 metni altıgenlerin içinde, Seviye 2 metni şekillerin dışında yer alır. |
| AlternatingPictureBlocks | `4` | Üstten alta bir dizi resmi göstermek için kullanılır. Metin, resmin sağında ya da solunda dönüşümlü olarak görünür. |
| AlternatingPictureCircles | `5` | Resim ve metin seti göstermek için kullanılır. Karşılık gelen metin, merkezdeki dairelerde yer alır; resimler soldan sağa dönüşümlü olarak sıralanır. |
| ArrowRibbon | `6` | İlgili ya da zıt kavramları bazı bağlantılarla göstermek için kullanılır; örneğin zıt kuvvetler. İlk iki Seviye 1 satırı oklarda metin olarak kullanılır. Kullanılmayan metin görünmez, ancak düzeni değiştirdiğinizde hâlâ kullanılabilir. |
| AscendingPictureAccentProcess | `7` | Açıklayıcı metinle birlikte yukarı doğru artan bir dizi resmi göstermek için kullanılır. Az miktarda metinle en iyi çalışır. |
| Balance | `8` | İki fikir arasındaki ilişkiyi ya da karşılaştırmayı göstermek için kullanılır. İlk iki Seviye 1 satırı, merkez noktasının bir tarafının üst kısmındaki metni temsil eder. Seviye 2 metni, merkez noktasının her iki tarafındaki dört şekle sınırlıdır. Denge, Seviye 2 metni içeren daha fazla şekle sahip tarafa kayar. Kullanılmayan metin görünmez, ancak düzeni değiştirdiğinizde hâlâ kullanılabilir. |
| BasicBendingProcess | `9` | Bir görev, süreç veya iş akışında ilerlemeyi veya sıralı adımları göstermek için kullanılır. Şekiller için yatay ve dikey alanı en üst düzeye çıkarır. |
| BasicBlockList | `10` | Sıralı olmayan ya da gruplanmış bilgi bloklarını göstermek için kullanılır. Şekiller için yatı ve dikey alanı en üst düzeye çıkarır. |
| BasicChevronProcess | `11` | İlerlemeyi, bir zaman çizelgesini, sıralı adımları veya hareketi/yönü vurgulamayı göstermek için kullanılır. Seviye 1 metni bir ok şeklinin içinde, Seviye 2 metni ok şekillerinin altında yer alır. |
| BasicCycle | `12` | Dairesel bir akışta aşama, görev veya olayların devam eden bir dizisini temsil eder. Bağlayıcı oklar ya da akıştan ziyade aşamaları/vadeleri vurgular. Yalnızca Seviye 1 metniyle en iyi çalışır. |
| BasicMatrix | `13` | Bütün içinde bileşenlerin ilişkisini dört bölgeye ayırarak gösterir. İlk dört Seviye 1 satırı bölgelere yerleştirilir. Kullanılmayan metin görünmez, ancak düzeni değiştirdiğinizde hâlâ kullanılabilir. |
| BasicPie | `14` | Bireysel parçaların bütün oluşturduğu durumu gösterir. İlk yedi Seviye 1 satırı eşit şekilde dağıtılmış dilim veya pasta şekilleriyle eşleşir. En üst Seviye 1 şekli, vurgulamak için pastanın geri kalanının dışında yer alır. Kullanılmayan metin görünmez, ancak düzeni değiştirdiğinizde hâlâ kullanılabilir. |
| BasicProcess | `15` | Bir görev, süreç veya iş akışında ilerlemeyi veya sıralı adımları göstermek için kullanılır. |
| BasicPyramid | `16` | En büyük bileşenin altta, yukarı doğru daralan bir piramit şeklinde orantılı, birbirine bağlanmış veya hiyerarşik ilişkileri göstermek için kullanılır. Seviye 1 metni piramit segmentlerinde, Seviye 2 metni her segmentin yanındaki şekillerde yer alır. |
| BasicRadial | `17` | Bir döngü içinde merkezi bir fikre ilişkin gösterim için kullanılır. İlk Seviye 1 satırı merkezi şekle, Seviye 2 metni çevredeki dairesel şekillere karşılık gelir. Kullanılmayan metin görünmez, ancak düzeni değiştirdiğinizde hâlâ kullanılabilir. |
| BasicTarget | `18` | Kapsam, gradyan veya hiyerarşik ilişkileri göstermek için kullanılır. İlk beş Seviye 1 satırı bir daireyle ilişkilidir. Kullanılmayan metin görünmez, ancak düzeni değiştirdiğinizde hâlâ kullanılabilir. |
| BasicTimeline | `19` | Bir görev, süreç veya iş akışındaki sıralı adımları ya da zaman çizelgesi bilgilerini göstermek için kullanılır. Hem Seviye 1 hem de Seviye 2 metinleriyle iyi çalışır. |
| BasicVenn | `20` | Çakışan ya da birbirine bağlı ilişkileri göstermek için kullanılır. İlk yedi Seviye 1 satırı bir daireyle eşleşir. Dört veya daha az Seviye 1 satırı varsa metin dairelerin içinde, daha fazlaysa dışındadır. Kullanılmayan metin görünmez, ancak düzeni değiştirdiğinizde hâlâ kullanılabilir. |
| BendingPictureAccentList | `21` | Sıralı olmayan ya da gruplanmış bilgi bloklarını göstermek için kullanılır. Küçük dairesel şekiller resim barındıracak şekilde tasarlanmıştır. Hem Seviye 1 hem de Seviye 2 metinleri iyi gösterir. Şekiller için yatay ve dikey alanı en üst düzeye çıkarır. |
| BendingPictureBlocks | `22` | Bir dizi resmi göstermek için kullanılır. Alt köşeyi kaplayan kutu az miktarda metin barındırabilir. |
| BendingPictureCaption | `23` | Sıralı bir dizi resmi göstermek için kullanılır. Alt köşeyi kaplayan kutu az miktarda metin barındırabilir. |
| BendingPictureCaptionList | `24` | Bir dizi resmi göstermek için kullanılır. Başlık ve açıklama her resmin altında bir açıklama şekli içinde yer alır. |
| BendingPictureSemiTransparentText | `25` | Bir dizi resmi göstermek için kullanılır. Yarı saydam bir kutu resmin alt kısmını kaplar ve tüm metin seviyelerini içerir. |
| BlockCycle | `26` | Dairesel bir akışta aşama, görev veya olayların devam eden bir dizisini temsil eder. Bağlayıcı oklar ya da akıştan ziyade aşamaları/vadeleri vurgular. |
| BubblePictureList | `27` | Bir dizi resmi göstermek için kullanılır. En fazla sekiz Seviye 1 resmi içerebilir. Kullanılmayan metin ve resimler görünmez, ancak düzeni değiştirdiğinizde hâlâ kullanılabilir. Az miktarda metinle en iyi çalışır. |
| CaptionedPictures | `28` | Çok seviyeli metinle resimler göstermek için kullanılır. Az miktarda Seviye 1 ve orta miktarda Seviye 2 metinle en iyi çalışır. |
| ChevronList | `29` | Bir bütün iş akışını oluşturan birkaç süreci göstermek için ilerleme sağlar. Aynı zamanda zıt süreçleri göstermek için de kullanılabilir. Seviye 1 metni sol taraftaki ilk ok şekline, Seviye 2 metni ise Seviye 1 metni içeren her şeklin yanındaki yatay alt adımlara karşılık gelir. |
| CircleAccentTimeline | `30` | Bir dizi olayı ya da zaman çizelgesi bilgisini göstermek için kullanılır. Seviye 1 metni daha büyük dairesel şekillerin yanında, Seviye 2 metni daha küçük dairesel şekillerin yanında yer alır. |
| CircleArrowProcess | `31` | Her öğe için destek metniyle birlikte sıralı öğeleri göstermek için kullanılır. Bu diyagram az miktarda Seviye 1 metniyle en iyi çalışır. |
| CirclePictureHierarchy | `32` | Bir organizasyonda hiyerarşik bilgi ya da raporlama ilişkilerini göstermek için kullanılır. Resimler daire içinde, karşılık gelen metin resimlerin yanında yer alır. |
| CircleRelationship | `33` | Merkezi bir fikre ilişkin ya da merkezden çıkan ilişkiyi göstermek için kullanılır. Seviye 2 metni sıralı olmayan şekilde eklenir ve beş öğeyle sınırlıdır. Yalnızca bir Seviye 1 öğesi bulunabilir. |
| CircularBendingProcess | `34` | Bir görev, süreç veya iş akışında uzun ya da doğrusal olmayan bir dizi adımı göstermek için kullanılır. Yalnızca Seviye 1 metniyle en iyi çalışır. Şekiller için yatay ve dikey alanı en üst düzeye çıkarır. |
| CircularPictureCallout | `35` | Merkezi bir fikir ve alt fikirleri ya da ilgili öğeleri göstermek için kullanılır. İlk resmin metni resmin alt kısmını kaplar. Diğer Seviye 1 şekilleri için karşılık gelen metin küçük dairesel resimlerin yanında yer alır. Bu diyagram metin olmadığında da iyi çalışır. |
| ClosedChevronProcess | `36` | Bir görev, süreç veya iş akışında ilerlemeyi, zaman çizelgesini veya sıralı adımları göstermek ya da hareketi/yönü vurgulamak için kullanılır. Başlangıç şeklinin bilgilerini vurgulamak için kullanılabilir. Yalnızca Seviye 1 metniyle en iyi çalışır. |
| ContinuousArrowProcess | `37` | Bir zaman çizelgesi ya da sıralı adımları bir görev, süreç veya iş akışında göstermek için kullanılır. Her Seviye 1 satırı ok şeklinin içinde yer aldığından Seviye 1 metniyle en iyi çalışır. Seviye 2 metni ok şeklinin dışında yer alır. |
| ContinuousBlockProcess | `38` | Bir görev, süreç veya iş akışında ilerlemeyi ya da sıralı adımları göstermek için kullanılır. Az miktarda Seviye 1 ve Seviye 2 metniyle en iyi çalışır. |
| ContinuousCycle | `39` | Dairesel bir akışta aşama, görev veya olayların devam eden bir dizisini temsil eder. Tüm bileşenler arasındaki bağlantıyı vurgular. Yalnızca Seviye 1 metniyle en iyi çalışır. |
| ContinuousPictureList | `40` | Birbirine bağlanmış bilgi gruplarını göstermek için kullanılır. Dairesel şekiller resim barındıracak şekilde tasarlanmıştır. |
| ConvergingArrows | `41` | Fikir ya da kavramların merkezi bir noktada birleştiğini göstermek için kullanılır. Yalnızca Seviye 1 metniyle en iyi çalışır. |
| ConvergingRadial | `42` | Dairesel bir akışta kavramların ya da bileşenlerin merkezi bir fikre ilişkisini göstermek için kullanılır. İlk Seviye 1 satırı merkezi dairesel şekle, Seviye 2 satırları çevredeki dikdörtgen şekillere karşılık gelir. Kullanılmayan metin görünmez, ancak düzeni değiştirdiğinizde hâlâ kullanılabilir. |
| CounterbalanceArrows | `43` | İki zıt fikri göstermek için kullanılır. İlk iki Seviye 1 satırı oklarla eşleşir ve Seviye 2 metniyle iyi çalışır. Kullanılmayan metin görünmez, ancak düzeni değiştirdiğinizde hâlâ kullanılabilir. |
| CycleMatrix | `44` | Dairesel bir ilerlemede merkezi bir fikre ilişkin gösterim için kullanılır. İlk dört Seviye 1 satırı dilim ya da pasta şekline, Seviye 2 metni ise dilimin yanındaki dikdörtgen şekle karşılık gelir. Kullanılmayan metin görünmez, ancak düzeni değiştirdiğinizde hâlâ kullanılabilir. |
| DescendingBlockList | `45` | İlgili fikir gruplarını ya da bilgi listelerini göstermek için kullanılır. Metin şekilleri yüksekliği azalarak sıralanır ve Seviye 1 metni dikey olarak gösterilir. |
| DescendingProcess | `46` | Aşağı doğru bir dizi olayı göstermek için kullanılır. İlk Seviye 1 metni okun üst kısmında, son Seviye 1 metni okun alt kısmında yer alır. Yalnızca ilk yedi Seviye 1 öğesi gösterilir. Az ila orta miktarda metinle en iyi çalışır. |
| DetailedProcess | `47` | Büyük miktarda Seviye 2 metniyle aşamaları göstermek için kullanılır. |
| DivergingArrows | `48` | Merkezi bir kaynaktan dışa doğru ilerleyen fikir ya da kavramları göstermek için kullanılır. Yalnızca Seviye 1 metniyle en iyi çalışır. |
| DivergingRadial | `49` | Dairesel bir akışta merkezi bir fikre ilişkin gösterim için kullanılır. İlk Seviye 1 satırı merkezi dairesel şekle karşılık gelir. Çevredeki daireler, merkezi fikri vurgular. Kullanılmayan metin görünmez, ancak düzeni değiştirdiğinizde hâlâ kullanılabilir. |
| Equation | `50` | Bir planı ya da sonucu betimleyen sıralı adımları ya da görevleri göstermek için kullanılır. Son Seviye 1 satırı eşittir işaretinin (=) ardından gelir. Yalnızca Seviye 1 metniyle en iyi çalışır. |
| FramedTextPicture | `51` | Resimleri, çerçeve içinde gösterilen karşılık gelen Seviye 1 metniyle birlikte göstermek için kullanılır. |
| Funnel | `52` | Bilgi filtresini ya da parçaların bir bütün içinde birleşmesini göstermek için kullanılır. Sonucun vurgulanmasını sağlar. En fazla dört Seviye 1 satırı içerebilir; dördüncü Seviye 1 satırı hununun altında, diğer satırlar dairesel şekille eşleşir. Kullanılmayan metin görünmez, ancak düzeni değiştirdiğinizde hâlâ kullanılabilir. |
| Gear | `53` | Birbirine kenetlenen fikirleri göstermek için kullanılır. İlk üç Seviye 1 satırı dişli şekline, karşılık gelen Seviye 2 metni dişlinin yanındaki dikdörtgenlere yerleştirilir. Kullanılmayan metin görünmez, ancak düzeni değiştirdiğinizde hâlâ kullanılabilir. |
| GridMatrix | `54` | İki eksen boyunca kavramların yerleşimini göstermek için kullanılır. Bütün yerine bireysel bileşenleri vurgular. İlk dört Seviye 1 satırı bölgelere yerleştirilir. Kullanılmayan metin görünmez, ancak düzeni değiştirdiğinizde hâlâ kullanılabilir. |
| GroupedList | `55` | Bilgi gruplarını ve alt gruplarını, bir görevin, sürecin veya iş akışının adımlarını ve alt adımlarını göstermek için kullanılır. Seviye 1 metni üst seviyedeki yatay şekillerle, Seviye 2 metni ise her üst seviye şeklin altındaki dikey alt adımlarla eşleşir. Alt grupları, alt adımları, hiyerarşik bilgiyi veya birden çok bilgi listesini vurgulamak için iyidir. |
| HalfCircleOrganizationChart | `56` | Bir organizasyonda hiyerarşik bilgi ya da raporlama ilişkilerini göstermek için kullanılır. Asistan şekilleri ve Org Chart asılı düzenleri bu düzenle birlikte kullanılabilir. |
| HexagonCluster | `57` | Resimleri ilgili açıklayıcı metinle birlikte göstermek için kullanılır. Küçük altıgenler resim-metin çiftini işaret eder. Az miktarda metinle en iyi çalışır. |
| Hierarchy | `58` | Üstten alta ilerleyen hiyerarşik ilişkileri göstermek için kullanılır. |
| HierarchyList | `59` | Gruplar arasında ilerleyen hiyerarşik ilişkileri göstermek için kullanılır. Bilgi gruplamak ya da listelemek için de kullanılabilir. |
| HorizontalBulletList | `60` | Sıralı olmayan ya da gruplanmış bilgi listelerini göstermek için kullanılır. Büyük miktarda metinle iyi çalışır. Tüm metin aynı vurguyu taşır ve yön ima edilmez. |
| HorizontalHierarchy | `61` | Yatay olarak ilerleyen hiyerarşik ilişkileri göstermek için kullanılır. Karar ağaçları için iyidir. |
| HorizontalLabeledHierarchy | `62` | Yatay ve hiyerarşik olarak gruplanmış ilişkileri gösterir. Başlık ya da Seviye 1 metnini vurgular. İlk Seviye 1 satırı hiyerarşinin başlangıcındaki şeklin içinde, ikinci ve sonraki satırlar uzun dikdörtgenlerin üst kısmında yer alır. |
| HorizontalMultiLevelHierarchy | `63` | Yatay olarak ilerleyen büyük miktarda hiyerarşik bilgiyi göstermek için kullanılır. Hiyerarşinin üst kısmı dikey olarak gösterilir. Bu düzen çok seviyeli hiyerarşileri destekler. |
| HorizontalOrganizationChart | `64` | Bir organizasyonda yatay olarak hiyerarşik bilgi ya da raporlama ilişkilerini göstermek için kullanılır. Asistan şekli ve Org Chart asılı düzenleri bu düzenle birlikte kullanılabilir. |
| HorizontalPictureList | `65` | Sıralı olmayan ya da gruplanmış bilgiyi, ilgili resimlere vurgu yaparak göstermek için kullanılır. Üst şekiller resim barındıracak şekilde tasarlanmıştır. |
| IncreasingArrowsProcess | `66` | Bir süreçte sıralı ve çakışan adımları göstermek için kullanılır. En fazla beş Seviye 1 öğesi bulunur. Seviye 2 geniş miktarda metin barındırabilir. |
| IncreasingCircleProcess | `67` | Her adımda dairenin içi artan bir dizi adımı göstermek için kullanılır. En fazla yedi Seviye 1 adımı, sınırsız Seviye 2 öğesi bulunur. Büyük miktarda Seviye 2 metniyle iyidir. |
| InvertedPyramid | `68` | En büyük bileşen üstte, aşağı doğru daralan bir piramit şeklinde orantılı, birbirine bağlanmış ya da hiyerarşik ilişkileri göstermek için kullanılır. Seviye 1 metni piramit segmentlerinde, Seviye 2 metni her segmentin yanındaki şekillerde yer alır. |
| LabeledHierarchy | `69` | Üstten alta ilerleyen ve hiyerarşik olarak gruplanmış ilişkileri gösterir. Başlık ya da Seviye 1 metnini vurgular. İlk Seviye 1 satırı hiyerarşinin başlangıcındaki şeklin içinde, sonraki tüm Seviye 1 satırları uzun dikdörtgenlerin solunda yer alır. |
| LinearVenn | `70` | Çakışan ilişkileri bir dizi içinde göstermek için kullanılır. Yalnızca Seviye 1 metniyle en iyi çalışır. |
| LinedList | `71` | Kategorilere ve alt kategorilere ayrılmış büyük miktarda metni göstermek için kullanılır. Birden çok metin seviyesiyle iyi çalışır. Aynı seviyedeki metinler çizgilerle ayrılır. |
| MultidirectionalCycle | `72` | Her yönde gerçekleşebilen bir dizi aşama, görev ya da olayı temsil eder. |
| NameandTitleOrganizationChart | `73` | Bir organizasyonda hiyerarşik bilgi ya da raporlama ilişkilerini göstermek için kullanılır. Başlık kutusuna metin girmek için daha küçük dikdörtgen şeklin içine doğrudan yazın. Asistan şekli ve Org Chart asılı düzenleri bu düzenle birlikte kullanılabilir. |
| NestedTarget | `74` | Kapsam ilişkilerini göstermek için kullanılır. İlk üç Seviye 1 satırı şekillerin sol üst metniyle eşleşir, Seviye 2 metni daha küçük şekillerle eşleşir. Az miktarda Seviye 2 satırıyla en iyi çalışır. Kullanılmayan metin görünmez, ancak düzeni değiştirdiğinizde hâlâ kullanılabilir. |
| NondirectionalCycle | `75` | Dairesel bir akışta devam eden bir dizi aşama, görev ya da olayı temsil eder. Tüm şekiller aynı öneme sahiptir. Yön göstermek gerekmediğinde iyidir. |
| OpposingArrows | `76` | İki zıt fikri ya da merkezi bir noktadan ayrılan fikirleri göstermek için kullanılır. İlk iki Seviye 1 satırı bir oka karşılık gelir. Kullanılmayan metin görünmez, ancak düzeni değiştirdiğinizde hâlâ kullanılabilir. |
| OpposingIdeas | `77` | İki zıt ya da çelişen fikri göstermek için kullanılır. Bir ya da iki Seviye 1 öğesi bulunabilir. Her Seviye 1 metni birden çok alt seviyeye sahip olabilir. Büyük miktarda metinle iyi çalışır. |
| OrganizationChart | `78` | Bir organizasyonda hiyerarşik bilgi ya da raporlama ilişkilerini göstermek için kullanılır. Asistan şekli ve Org Chart asılı düzenleri bu düzenle birlikte kullanılabilir. |
| PhasedProcess | `79` | Bir sürecin üç aşamasını göstermek için kullanılır. En fazla üç Seviye 1 öğesi bulunur. İlk iki Seviye 1 öğesi dört Seviye 2 öğesi barındırabilir, üçüncü Seviye 1 öğesi sınırsız sayıda Seviye 2 öğesi barındırabilir. Az miktarda metinle en iyi çalışır. |
| PictureAccentBlocks | `80` | Köşeden başlayan bloklarda bir grup resmi göstermek için kullanılır. Karşılık gelen metin dikey olarak görüntülenir. Başlık ya da alt-başlık slaytlarında, belge bölüm ayırıcılarında vurgu olarak iyidir. |
| PictureAccentList | `81` | Gruplanmış ya da ilgili bilgiyi göstermek için kullanılır. Üst köşedeki küçük şekiller resim barındıracak şekilde tasarlanmıştır. Seviye 2 metnini Seviye 1 metnine göre öne çıkarır ve büyük miktarda Seviye 2 metni için iyi bir seçimdir. |
| PictureAccentProcess | `82` | Bir görev, süreç ya da iş akışındaki sıralı adımları göstermek için kullanılır. Arkadaki dikdörtgen şekiller resim barındıracak şekilde tasarlanmıştır. |
| PictureCaptionList | `83` | Sıralı olmayan ya da gruplanmış bilgi bloklarını göstermek için kullanılır. Üst şekiller resim barındıracak şekilde tasarlanmıştır ve resimler metinden öne çıkar. Kısa metin açıklamalarıyla resimler için iyidir. |
| PictureGrid | `84` | Kare bir ızgara üzerinde düzenlenmiş resimleri göstermek için kullanılır. Az miktarda Seviye 1 metniyle en iyisidir; bu metin resmin üstünde yer alır. |
| PictureLineup | `85` | Yan yana bir dizi resmi göstermek için kullanılır. Seviye 1 metni resmin üst kısmını kaplar. Seviye 2 metni resmin altında yer alır. |
| PictureStrips | `86` | Üstten alta bir dizi resmi, her birinin yanında Seviye 1 metni olacak şekilde göstermek için kullanılır. |
| PieProcess | `87` | Her dilimin büyüklüğü artan bir süreç adımlarını, en fazla yedi şekil olmak üzere göstermek için kullanılır. Seviye 1 metni dikey olarak görüntülenir. |
| PlusandMinus | `88` | İki fikrin artı ve eksilerini göstermek için kullanılır. Her Seviye 1 metni birden çok alt seviyeye sahip olabilir. Büyük miktarda metinle iyidir. En fazla iki Seviye 1 öğesi bulunur. |
| ProcessArrows | `89` | Bir süreç ya da iş akışını gösteren bilgiyi göstermek için kullanılır. Seviye 1 metni dairesel şekillerde, Seviye 2 metni ok şekillerinde yer alır. Az metinle ve hareketi/yönü vurgulamak için en iyisidir. |
| ProcessList | `90` | Bir görev, süreç ya da iş akışında birden çok bilgi grubu ya da adım-alt adım gösterir. Seviye 1 metni üst yatay şekillerle, Seviye 2 metni her üst seviyedeki şeklin altındaki dikey alt adımlarla eşleşir. |
| PyramidList | `91` | Orantılı, birbirine bağlanmış ya da hiyerarşik ilişkileri gösterir. Metin, piramidin arka planının üstündeki dikdörtgen şekillerde yer alır. |
| RadialCluster | `92` | Merkezi bir fikir ya da temaya ilişkin veriyi göstermek için kullanılır. En üst Seviye 1 metni ortada, Seviye 2 metni çevredeki şekillerde yer alır. En fazla yedi Seviye 2 şekli içerebilir. Kullanılmayan metin görünmez, ancak düzeni değiştirdiğinizde hâlâ kullanılabilir. Az miktarda metinle en iyisidir. |
| RadialCycle | `93` | Merkezi bir fikre ilişkin gösterim için kullanılır. Hem ortadaki dairedeki bilgi hem de dış halkadaki dairelerin merkezi fikre katkısı vurgulanır. İlk Seviye 1 satırı merkezi daireye, Seviye 2 metni dış halkadaki dairelere karşılık gelir. Kullanılmayan metin görünmez, ancak düzeni değiştirdiğinizde hâlâ kullanılabilir. |
| RadialList | `94` | Merkezi bir fikre ilişkin ilişkileri bir döngü içinde göstermek için kullanılır. Merkez şekil bir resim barındırabilir. Seviye 1 metni daha küçük dairelerde, ilgili Seviye 2 metni ise bu dairelerin yanında yer alır. |
| RadialVenn | `95` | Çakışan ilişkileri ve bir döngü içinde merkezi bir fikre ilişkin ilişkiyi göstermek için kullanılır. İlk Seviye 1 satırı merkezi şekle, Seviye 2 satırları çevredeki dairesel şekillere karşılık gelir. Kullanılmayan metin görünmez, ancak düzeni değiştirdiğinizde hâlâ kullanılabilir. |
| RandomToResultProcess | `96` | Kaotik fikirlerin bir dizi adım aracılığıyla birleşik bir hedefe ya da fikre nasıl ulaşabileceğini göstermek için kullanılır. Birden çok Seviye 1 metni desteklenir, ancak ilk ve son Seviye 1 şekli sabittir. Az miktarda Seviye 1 ve orta miktarda Seviye 2 metniyle en iyisidir. |
| RepeatingBendingProcess | `97` | Bir görev, süreç ya da iş akışında ilerlemeyi ya da sıralı adımları göstermek için kullanılır. Şekiller için yatay ve dikey alanı en üst düzeye çıkarır. |
| ReverseList | `98` | İki öğe arasında değişim göstermek için kullanılır. Yalnızca ilk iki metin öğesi görüntülenir ve her öğe büyük miktarda metin içerebilir. İki öğe arasındaki değişimi ya da sıralama kaymasını göstermek için iyidir. |
| SegmentedCycle | `99` | Dairesel bir akışta bir dizi aşama, görev ya da olayı göstermek için kullanılır. Birbirine bağlanmış parçaları vurgular. İlk yedi Seviye 1 satırı dilim ya da pasta şekline karşılık gelir. Kullanılmayan metin görünmez, ancak düzeni değiştirdiğinizde hâlâ kullanılabilir. |
| SegmentedProcess | `100` | Bir görev, süreç ya da iş akışında ilerlemeyi ya da sıralı adımları göstermek için kullanılır. Seviye 2 metni vurgulanır; çünkü her satır ayrı bir şekilde yer alır. |
| SegmentedPyramid | `101` | Kapsam, orantı ya da birbirine bağlanmış ilişkileri göstermek için kullanılır. İlk dokuz Seviye 1 satırı üçgen şekillerde yer alır. Kullanılmayan metin görünmez, ancak düzeni değiştirdiğinizde hâlâ kullanılabilir. Yalnızca Seviye 1 metniyle en iyi çalışır. |
| SnapshotPictureList | `102` | Açıklayıcı metinle birlikte resimleri göstermek için kullanılır. Seviye 2 metni bilgi listeleri gösterebilir. Büyük miktarda metinle iyidir. |
| SpiralPicture | `103` | En fazla beş resmi, karşılık gelen Seviye 1 başlıklarıyla merkeze doğru sarmal bir biçimde göstermek için kullanılır. |
| SquareAccentList | `104` | Kategorilere ayrılmış bilgi listelerini göstermek için kullanılır. Seviye 2 metni küçük kare şeklin yanında görünür. Büyük miktarda Seviye 2 metniyle iyidir. |
| StackedList | `105` | Bir görev, süreç ya da iş akışında bilgi gruplarını veya adımları göstermek için kullanılır. Dairesel şekiller Seviye 1 metnini, karşılık gelen dikdörtgenler Seviye 2 metnini barındırır. Çok sayıda detay ve az Seviye 1 metni için iyidir. |
| StackedVenn | `106` | Çakışan ilişkileri göstermek için kullanılır. Büyüme ya da gradyanı vurgulamak için iyi bir seçimdir. Yalnızca Seviye 1 metniyle en iyisidir. İlk yedi Seviye 1 satırı dairesel şekle karşılık gelir. Kullanılmayan metin görünmez, ancak düzeni değiştirdiğinizde hâlâ kullanılabilir. |
| StaggeredProcess | `107` | Aşamalı bir aşağı doğru ilerlemeyi göstermek için kullanılır. İlk beş Seviye 1 satırı bir dikdörtgenle eşleşir. Kullanılmayan metin görünmez, ancak düzeni değiştirdiğinizde hâlâ kullanılabilir. |
| StepDownProcess | `108` | Alt adımlar ve alt-adımlarla birlikte aşağı doğru bir süreci göstermek için kullanılır. Az miktarda metinle en iyisidir. |
| StepUpProcess | `109` | Yukarı doğru bir dizi adım ya da bilgi listesini göstermek için kullanılır. |
| SubStepProcess | `110` | Her Seviye 1 metni arasına alt-adımlar eklenmiş çok-adımlı bir süreci göstermek için kullanılır. Az miktarda metinle en iyisidir ve en fazla yedi Seviye 1 adımı içerir. Her Seviye 1 adımı sınırsız alt-adım barındırabilir. |
| TableHierarchy | `111` | Üstten alta oluşan bilgi gruplarını ve her grubun içindeki hiyerarşileri göstermek için kullanılır. Bu düzen bağlayıcı çizgiler içermez. |
| TableList | `112` | Eş değerde gruplanmış ya da ilgili bilgiyi göstermek için kullanılır. İlk Seviye 1 satırı üst şekille eşleşir, Seviye 2 metni ise sonraki listeler için kullanılır. |
| TargetList | `113` | Birbirine bağlı ya da çakışan bilgiyi göstermek için kullanılır. İlk yedi Seviye 1 satırı dikdörtgen şekillerde yer alır. Kullanılmayan metin görünmez, ancak düzeni değiştirdiğinizde hâlâ kullanılabilir. Hem Seviye 1 hem de Seviye 2 metniyle iyidir. |
| TextCycle | `114` | Dairesel bir akışta aşama, görev veya olayların devam eden bir dizisini temsil eder. Okları ya da akışı, aşamaları/vadeleri vurgulamaktan ziyade öne çıkarır. Yalnızca Seviye 1 metniyle en iyisidir. |
| TitlePictureLineup | `115` | Her biri kendi başlığı ve açıklaması olan bir dizi resmi göstermek için kullanılır. Seviye 1 metni resmin üzerindeki kutuda, Seviye 2 metni resmin altında yer alır. |
| TitledMatrix | `116` | Dört bölgenin bütünle ilişkisini göstermek için kullanılır. İlk Seviye 1 satırı merkezi şekle, ilk dört Seviye 2 satırı bölgelere karşılık gelir. Kullanılmayan metin görünmez, ancak düzeni değiştirdiğinizde hâlâ kullanılabilir. |
| TitledPictureAccentList | `117` | Her Seviye 2 metni için bir vurgu resmi içeren bilgi listelerini göstermek için kullanılır. Seviye 1 metni listenin üst kısmındaki ayrı bir kutuda görüntülenir. |
| TitledPictureBlocks | `118` | Bir dizi resmi göstermek için kullanılır. Seviye 1 metni her resmin üstünde, Seviye 2 metni ise yan tarafta ve hafifçe resmin üzerine çakışık olarak yer alır. |
| TrapezoidList | `119` | Eş değerde gruplanmış ya da ilgili bilgiyi göstermek için kullanılır. Büyük miktarda metinle iyidir. |
| UpwardArrow | `120` | Bir görev, süreç ya da iş akışında yukarı doğru bir ilerleme ya da adımları göstermek için kullanılır. İlk beş Seviye 1 satırı okun bir noktasına karşılık gelir. Az metinle en iyisidir. Kullanılmayan metin görünmez, ancak düzeni değiştirdiğinizde hâlâ kullanılabilir. |
| VerticalAccentList | `121` | Bilgi listelerini göstermek için kullanılır. Seviye 2 metni, dikey şeritlerin üzerindeki dikdörtgen şekillerde yer alır. Seviye 2 metni Seviye 1 metnine göre öne çıkar ve orta miktarda Seviye 2 metni için iyi bir seçimdir. |
| VerticalArrowList | `122` | Ortak bir hedefe doğru hareket eden bir görev, süreç ya da iş akışındaki ilerleme ya da sıralı adımları göstermek için kullanılır. Bilgi listeleri için iyidir. |
| VerticalBendingProcess | `123` | Bir görev, süreç ya da iş akışında ilerlemeyi ya da sıralı adımları göstermek için kullanılır. Şekiller için yatay ve dikey alanı en üst düzeye çıkarır. Yön ya da hareketten ziyade şekiller arasındaki ilişkilere daha çok vurgu yapar. |
| VerticalBlockList | `124` | Bir görev, süreç ya da iş akışında bilgi gruplarını ya da adımları göstermek için kullanılır. Büyük miktarda Seviye 2 metniyle iyidir. Ana nokta ve birden çok alt nokta içeren metinler için iyi bir seçimdir. |
| VerticalBoxList | `125` | Özellikle büyük miktarda Seviye 2 metni içeren birden çok bilgi grubunu göstermek için kullanılır. Bilgi listeleri için iyi bir seçimdir. |
| VerticalBulletList | `126` | Sıralı olmayan ya da gruplanmış bilgi bloklarını göstermek için kullanılır. Uzun başlıklar ya da üst seviye bilgiler içeren listeler için iyidir. |
| VerticalChevronList | `127` | Bir görev, süreç ya da iş akışında ilerlemeyi ya da sıralı adımları göstermek ya da hareketi/yönü vurgulamak için kullanılır. Seviye 2 metni Seviye 1 metnine göre öne çıkar ve büyük miktarda Seviye 2 metni için iyi bir seçimdir. |
| VerticalCircleList | `128` | Sıralı ya da gruplanmış verileri göstermek için kullanılır. Seviye 1 metni büyük dairesel şeklin yanında görüntülenir. Alt seviyeler daha küçük dairesel şekillerle ayrılır. |
| VerticalCurvedList | `129` | Eğimli bir bilgi listesini göstermek için kullanılır. Vurgu daire şekillerine resim eklemek için resim doldurma uygulanır. |
| VerticalEquation | `130` | Bir planı ya da sonucu betimleyen sıralı adımları ya da görevleri göstermek için kullanılır. Son Seviye 1 satırı ok sonrası yer alır. Yalnızca Seviye 1 metniyle en iyisidir. |
| VerticalPictureAccentList | `131` | Sıralı olmayan ya da gruplanmış bilgi bloklarını göstermek için kullanılır. Küçük daireler resim barındıracak şekilde tasarlanmıştır. |
| VerticalPictureList | `132` | Sıralı olmayan ya da gruplanmış bilgi bloklarını göstermek için kullanılır. Sol taraftaki küçük şekiller resim barındıracak şekilde tasarlanmıştır. |
| VerticalProcess | `133` | Üstten alta bir görev, süreç ya da iş akışındaki ilerlemeyi ya da sıralı adımları göstermek için kullanılır. Dikey alan sınırlı olduğundan yalnızca Seviye 1 metniyle en iyisidir. |
| Custom | `134` | Özel bir düzen şablonuna sahip bir SmartArt diyagramını temsil eder |
| PictureOrganizationChart | `135` | Bir organizasyonda hiyerarşik bilgi ya da raporlama ilişkilerini, karşılık gelen resimlerle göstermek için kullanılır. Asistan şekli ve Org Chart asılı düzenleri bu düzenle birlikte kullanılabilir. |

### See Also

* namespace [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->