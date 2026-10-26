---
title: SmartArtLayoutType
second_title: Aspose.Slides için C++ API Referansı
description: Bir SmartArt diyagramının yerleşim tipini temsil eder.
type: docs
weight: 157
url: /tr/aspose.slides.smartart/smartartlayouttype/
---
## SmartArtLayoutType enum

Bir [SmartArt](../smartart/) diyagramının düzen tipini temsil eder.

```cpp
enum class SmartArtLayoutType
```

### Değerler

| Name | Value | Description |
| --- | --- | --- |
| AccentProcess | 0 | Bir görev, işlem veya iş akışında bir ilerleme, zaman çizelgesi veya ardışık adımları göstermek için kullanılır. Hem Level 1 hem Level 2 metni göstermede iyidir. |
| AccentedPicture | 1 | Merkezde fotoğrafik bir fikir ve yanlarda ilgili fikirleri göstermek için kullanılır. Üst Level 1 metni merkezi resmin üzerindedir. Diğer Level 1 şekillerinin karşılık gelen metni küçük dairesel resimlerin yanındadır. Bu düzen metinsiz de iyi çalışır. |
| AlternatingFlow | 2 | Bilgi gruplarını veya bir görev, işlem veya iş akışındaki ardışık adımları göstermek için kullanılır. Bilgi grupları arasındaki etkileşim veya ilişkileri vurgular. |
| AlternatingHexagons | 3 | Birbiriyle bağlantılı fikirler serisini temsil etmek için kullanılır. Level 1 metni altıgenlerin içinde, Level 2 metni şekillerin dışında görünür. |
| AlternatingPictureBlocks | 4 | Üstten alta bir dizi resmi göstermek için kullanılır. Metin resmin sağında veya solunda dönüşümlü olarak yer alır. |
| AlternatingPictureCircles | 5 | Resimlerle birlikte bir metin seti göstermek için kullanılır. İlgili metin, merkezi dairelerde görünür ve resimler soldan sağa dönüşümlü yer alır. |
| ArrowRibbon | 6 | İlişkili veya zıt kavramları bazı bağlantılarla göstermek için kullanılır, örneğin zıt güçler. Level 1 metninin ilk iki satırı okların içinde kullanılır. Kullanılmayan metin görünmez, ancak düzen değiştirildiğinde tekrar kullanılabilir. |
| AscendingPictureAccentProcess | 7 | Açıklayıcı metinle yükselen bir dizi resmi göstermek için kullanılır. Az miktarda metinle en iyi çalışır. |
| Balance | 8 | İki fikir arasındaki ilişkiyi karşılaştırmak veya göstermek için kullanılır. Level 1 metninin ilk iki satırı merkez noktasının bir tarafının üst kısmında yer alır. Level 2 metni, merkez noktasının her iki tarafındaki dört şekille sınırlıdır. Denge, Level 2 metni içeren daha çok şekle sahip tarafa kayar. Kullanılmayan metin görünmez, ancak düzen değiştirildiğinde tekrar kullanılabilir. |
| BasicBendingProcess | 9 | Bir görev, işlem veya iş akışında bir ilerleme veya ardışık adımları göstermek için kullanılır. Şekiller için hem yatay hem dikey alanı en üst düzeye çıkarır. |
| BasicBlockList | 10 | Sıralı olmayan veya gruplanmış bilgi bloklarını göstermek için kullanılır. Şekiller için hem yatay hem dikey alanı en üst düzeye çıkarır. |
| BasicChevronProcess | 11 | Bir ilerleme, zaman çizelgesi, ardışık adımlar veya hareketi/v yönünü vurgulamak için kullanılır. Level 1 metni ok şeklinde, Level 2 metni okların altında görünür. |
| BasicCycle | 12 | Dairesel akışta aşamaların, görevlerin veya olayların devam eden bir dizisini temsil eder. Bağlantı oklarından ziyade aşamaları vurgular. Yalnızca Level 1 metniyle en iyi çalışır. |
| BasicMatrix | 13 | Bileşenlerin bütünle ilişkisini dört bölge içinde gösterir. Level 1 metninin ilk dört satırı bölgelere dağıtılır. Kullanılmayan metin görünmez, ancak düzen değiştirildiğinde tekrar kullanılabilir. |
| BasicPie | 14 | Bireysel parçaların bütün oluşturmasını gösterir. Level 1 metninin ilk yedi satırı eşit dağıtılmış dilim veya pasta şekilleriyle eşleşir. Üst Level 1 metin şekli, vurgulamak için pastanın dışındadır. Kullanılmayan metin görünmez, ancak düzen değiştirildiğinde tekrar kullanılabilir. |
| BasicProcess | 15 | Bir görev, işlem veya iş akışında bir ilerleme veya ardışık adımları göstermek için kullanılır. |
| BasicPyramid | 16 | Altında en büyük bileşen, yukarıya doğru daralan bir piramitle orantılı, bağlanmış veya hiyerarşik ilişkileri gösterir. Level 1 metni piramit segmentlerinde, Level 2 metni her segmentin yanındaki şekillerde görünür. |
| BasicRadial | 17 | Bir döngüde merkezi bir fikre ilişkinliği göstermek için kullanılır. Level 1 metninin ilk satırı merkezi şekle, Level 2 metni çevresel dairesel şekillere karşılık gelir. Kullanılmayan metin görünmez, ancak düzen değiştirildiğinde tekrar kullanılabilir. |
| BasicTarget | 18 | Kapsam, derecelendirme veya hiyerarşik ilişkileri göstermek için kullanılır. Level 1 metninin ilk beş satırı bir daireyle ilişkilidir. Kullanılmayan metin görünmez, ancak düzen değiştirildiğinde tekrar kullanılabilir. |
| BasicTimeline | 19 | Bir görev, işlem veya iş akışındaki ardışık adımları veya zaman çizelgesi bilgisini göstermek için kullanılır. Hem Level 1 hem Level 2 metniyle iyi çalışır. |
| BasicVenn | 20 | Örtüşen veya bağlantılı ilişkileri gösterir. Level 1 metninin ilk yedi satırı bir daireyle eşleşir. Dört ya da daha az satır varsa metin dairelerin içinde, daha fazlaysa dışındadır. Kullanılmayan metin görünmez, ancak düzen değiştirildiğinde tekrar kullanılabilir. |
| BendingPictureAccentList | 21 | Sıralı olmayan veya gruplanmış bilgi bloklarını göstermek için kullanılır. Küçük dairesel şekiller resim içerecek şekilde tasarlanmıştır. Hem Level 1 hem Level 2 metni için iyidir. Şekiller için hem yatay hem dikey alanı en üst düzeye çıkarır. |
| BendingPictureBlocks | 22 | Bir dizi resmi göstermek için kullanılır. Alt köşeyi kaplayan kutu az miktarda metin içerebilir. |
| BendingPictureCaption | 23 | Ardışık bir dizi resmi göstermek için kullanılır. Alt köşeyi kaplayan kutu az miktarda metin içerebilir. |
| BendingPictureCaptionList | 24 | Bir dizi resmi göstermek için kullanılır. Başlık ve açıklama, her resmin altındaki bir çağrı şeklide görünür. |
| BendingPictureSemiTransparentText | 25 | Bir dizi resmi göstermek için kullanılır. Yarı şeffaf bir kutu resmin alt kısmını kaplar ve tüm metin seviyelerini içerir. |
| BlockCycle | 26 | Dairesel akışta aşamaların, görevlerin veya olayların devam eden bir dizisini temsil eder. Bağlantı oklarından ziyade aşamaları vurgular. |
| BubblePictureList | 27 | Bir dizi resmi göstermek için kullanılır. En fazla sekiz Level 1 resim içerebilir. Kullanılmayan metin ve resimler görünmez, ancak düzen değiştirildiğinde tekrar kullanılabilir. Az miktarda metinle en iyi çalışır. |
| CaptionedPictures | 28 | Çok seviyeli metinle resimleri göstermek için kullanılır. Az miktarda Level 1 metin ve orta miktarda Level 2 metinle en iyi çalışır. |
| ChevronList | 29 | Bir genel iş akışını oluşturan birkaç süreçte ilerlemeyi göstermek için kullanılır. Aynı zamanda zıt süreçleri göstermek için de kullanılır. Level 1 metni sol taraftaki ilk ok şekline, Level 2 metni ise Level 1 metni içeren her şeklin yatay alt adımlarına karşılık gelir. |
| CircleAccentTimeline | 30 | Bir dizi olayı veya zaman çizelgesi bilgisini göstermek için kullanılır. Level 1 metni büyük dairesel şekillerin yanında, Level 2 metni daha küçük dairesel şekillerin yanında görünür. |
| CircleArrowProcess | 31 | Her öğe için destek metniyle ardışık öğeleri göstermek için kullanılır. Bu diyagram az miktarda Level 1 metinle en iyi çalışır. |
| CirclePictureHierarchy | 32 | Bir organizasyondaki hiyerarşik bilgi veya raporlama ilişkilerini göstermek için kullanılır. Resimler dairelerde, ilgili metin resimlerin yanında görünür. |
| CircleRelationship | 33 | Merkezi bir fikir ile ilişkisini veya ondan bağlantısını göstermek için kullanılır. Level 2 metni sıralı olmayan şekilde eklenir ve beş öğe ile sınırlıdır. Sadece bir Level 1 öğe bulunabilir. |
| CircularBendingProcess | 34 | Bir görev, işlem veya iş akışında uzun veya doğrusal olmayan bir dizi ya da adımları göstermek için kullanılır. Yalnızca Level 1 metniyle en iyi çalışır. Şekiller için hem yatay hem dikey alanı en üst düzeye çıkarır. |
| CircularPictureCallout | 35 | Merkezi bir fikir ve alt fikirleri veya ilişkili öğeleri göstermek için kullanılır. İlk resim için metin resmin alt kısmını kaplar. Diğer Level 1 şekillerinin karşılık gelen metni küçük dairesel resimlerin yanında görünür. Bu diyagram metinsiz de iyi çalışır. |
| ClosedChevronProcess | 36 | Bir ilerleme, zaman çizelgesi veya ardışık adımları göstermek ve hareketi/v yönünü vurgulamak için kullanılır. Başlangıç şeklinin bilgisini vurgulamak için kullanılabilir. Yalnızca Level 1 metniyle en iyi çalışır. |
| ContinuousArrowProcess | 37 | Bir zaman çizelgesi veya ardışık adımları göstermek için kullanılır. Her Level 1 metin satırı ok şeklinde içinde yer alır, bu yüzden Level 1 metniyle en iyi çalışır. Level 2 metni ok şeklinin dışında görünür. |
| ContinuousBlockProcess | 38 | Bir ilerleme veya ardışık adımları göstermek için kullanılır. Minimum Level 1 ve Level 2 metinle en iyi çalışır. |
| ContinuousCycle | 39 | Dairesel akışta aşamaların, görevlerin veya olayların devam eden bir dizisini temsil eder. Tüm bileşenler arasındaki bağlantıyı vurgular. Yalnızca Level 1 metniyle en iyi çalışır. |
| ContinuousPictureList | 40 | Birbiriyle bağlantılı bilgi gruplarını göstermek için kullanılır. Dairesel şekiller resim içerecek şekilde tasarlanmıştır. |
| ConvergingArrows | 41 | Fikirleri veya kavramları merkezi bir noktada birleştirmek için kullanılır. Yalnızca Level 1 metniyle en iyi çalışır. |
| ConvergingRadial | 42 | Kavramların veya bileşenlerin bir döngüde merkezi bir fikre ilişkisini göstermek için kullanılır. Level 1 metninin ilk satırı merkezi dairesel şekle, Level 2 metni çevresel dikdörtgen şekillere karşılık gelir. Kullanılmayan metin görünmez, ancak düzen değiştirildiğinde tekrar kullanılabilir. |
| CounterbalanceArrows | 43 | İki zıt fikir veya kavramı göstermek için kullanılır. Level 1 metninin ilk iki satırı bir oka karşılık gelir ve Level 2 metniyle iyi çalışır. Kullanılmayan metin görünmez, ancak düzen değiştirildiğinde tekrar kullanılabilir. |
| CycleMatrix | 44 | Döngüsel bir ilerlemede merkezi bir fikre ilişkinliği göstermek için kullanılır. Level 1 metninin ilk dört satırı bir dilim veya pasta şekline karşılık gelir, Level 2 metni dilim/pasta şeklinin yanındaki dikdörtgen içinde görünür. Kullanılmayan metin görünmez, ancak düzen değiştirildiğinde tekrar kullanılabilir. |
| DescendingBlockList | 45 | İlgili fikirleri veya bilgi listelerini gruplamak için kullanılır. Metin şekilleri yüksekliği azalacak şekilde sıralanır ve Level 1 metni dikey olarak görüntülenir. |
| DescendingProcess | 46 | Alçalmalı bir olay serisini göstermek için kullanılır. İlk Level 1 metin okun üstünde, son Level 1 metin okun altında görüntülenir. Yalnızca ilk yedi Level 1 öğe görünür. Az ila orta miktarda metinle en iyi çalışır. |
| DetailedProcess | 47 | Büyük miktarda Level 2 metinle aşamalar arasında bir ilerleme göstermek için kullanılır. |
| DivergingArrows | 48 | Fikirleri veya kavramları merkezi bir kaynaktan dışa doğru ilerletmek için kullanılır. Yalnızca Level 1 metniyle en iyi çalışır. |
| DivergingRadial | 49 | Bir döngüde merkezi bir fikre ilişkinliği göstermek için kullanılır. İlk Level 1 satır merkezi dairesel şekle karşılık gelir. Çevresel daireleri, merkezi fikri değil, vurgular. Kullanılmayan metin görünmez, ancak düzen değiştirildiğinde tekrar kullanılabilir. |
| Equation | 50 | Ardışık adımları veya bir plan ya da sonucu gösteren görevleri göstermek için kullanılır. Son Level 1 satır eşittir işaretinden (=) sonra görünür. Yalnızca Level 1 metniyle en iyi çalışır. |
| FramedTextPicture | 51 | Resimleri, çerçeve içinde görüntülenen ilgili Level 1 metniyle göstermek için kullanılır. |
| Funnel | 52 | Bilgi filtrasyonunu veya parçaların bir bütünde birleşmesini göstermek için kullanılır. Sonuç vurgulanır. En fazla dört Level 1 metin satırı içerebilir; bu dört satırın sonuncusu huninin altında görünür, diğer satırlar dairesel şekle karşılık gelir. Kullanılmayan metin görünmez, ancak düzen değiştirildiğinde tekrar kullanılabilir. |
| Gear | 53 | Birbirine geçişli fikirleri göstermek için kullanılır. Level 1 metninin ilk üç satırı dişli şekle, karşılık gelen Level 2 metni dişlinin yanındaki dikdörtgenlerde görünür. Kullanılmayan metin görünmez, ancak düzen değiştirildiğinde tekrar kullanılabilir. |
| GridMatrix | 54 | İki eksen boyunca kavramların yerleşimini göstermek için kullanılır. Bütün yerine bireysel bileşenleri vurgular. Level 1 metninin ilk dört satırı çeyreklerde görünür. Kullanılmayan metin görünmez, ancak düzenleri değiştirdiğinizde kullanılabilir kalır. |
| GroupedList | 55 | Bilgi gruplarını ve alt gruplarını, ya da bir görev, süreç veya iş akışındaki adımları ve alt adımları göstermek için kullanılır. Level 1 metni üst düzey yatay şekillere karşılık gelir, Level 2 metni ise her ilgili üst düzey şeklin altındaki dikey alt adımlara karşılık gelir. Alt grupları veya alt adımları, hiyerarşik bilgiyi veya birden çok bilgi listesini vurgulamak için iyidir. |
| HalfCircleOrganizationChart | 56 | Bir organizasyonda hiyerarşik bilgi veya raporlama ilişkilerini göstermek için kullanılır. Bu düzenle yardımcı şekiller ve Org Chart asılı düzenleri mevcuttur. |
| HexagonCluster | 57 | İlişkili açıklayıcı metinle birlikte resimleri göstermek için kullanılır. Küçük altıgenler resim ve metin çiftini gösterir. Az miktarda metinle en iyi çalışır. |
| Hierarchy | 58 | Üstten alta doğru ilerleyen hiyerarşik ilişkileri göstermek için kullanılır. |
| HierarchyList | 59 | Gruplar arasında ilerleyen hiyerarşik ilişkileri göstermek için kullanılır. Ayrıca bilgiyi gruplamak veya listelemek için de kullanılabilir. |
| HorizontalBulletList | 60 | Sırasız veya gruplanmış bilgi listelerini göstermek için kullanılır. Çok miktarda metinle iyi çalışır. Tüm metin aynı vurgu seviyesine sahiptir ve yön ima edilmez. |
| HorizontalHierarchy | 61 | Yatay olarak ilerleyen hiyerarşik ilişkileri göstermek için kullanılır. Karar ağaçları için iyidir. |
| HorizontalLabeledHierarchy | 62 | Yatay olarak ilerleyen ve hiyerarşik olarak gruplanmış hiyerarşik ilişkileri göstermek için kullanılır. Başlık veya level 1 metni vurgular. Level 1 metninin ilk satırı hiyerarşinin başındaki şekilde görünür, ikinci ve sonraki tüm Level 1 satırları uzun dikdörtgenlerin üst kısmında görünür. |
| HorizontalMultiLevelHierarchy | 63 | Yatay olarak ilerleyen büyük miktarda hiyerarşik bilgiyi göstermek için kullanılır. Hiyerarşinin üst kısmı dikey olarak gösterilir. Bu düzen hiyerarşide birçok seviyeyi destekler. |
| HorizontalOrganizationChart | 64 | Hiyerarşik bilgiyi yatay olarak veya bir organizasyondaki raporlama ilişkilerini göstermek için kullanılır. Bu düzenle yardımcı şekil ve Org Chart asılı düzenleri mevcuttur. |
| HorizontalPictureList | 65 | İlgili resimlere vurgu yaparak sırasız veya gruplanmış bilgiyi göstermek için kullanılır. Üst şekiller resim barındıracak şekilde tasarlanmıştır. |
| IncreasingArrowsProcess | 66 | Bir süreçte sıralı ve üst üste binen adımları göstermek için kullanılır. Beş Level 1 öğeyle sınırlıdır. Level 2 büyük miktarda metin içerebilir. |
| IncreasingCircleProcess | 67 | Adım adım ilerleyen bir dizi adımı göstermek için kullanılır; dairenin iç kısmı her adımda büyür. Yedi Level 1 adımla sınırlıdır ancak Level 2 öğeleri sınırsızdır. Büyük miktarda Level 2 metniyle iyi çalışır. |
| InvertedPyramid | 68 | En büyük bileşen üstte ve daralan bir biçimde, orantılı, birbirine bağlı veya hiyerarşik ilişkileri göstermek için kullanılır. Level 1 metni piramit bölümlerinde, Level 2 metni ise her bölümün yanındaki şekillerde görünür. |
| LabeledHierarchy | 69 | Üstten aşağı doğru ilerleyen ve hiyerarşik olarak gruplanmış hiyerarşik ilişkileri göstermek için kullanılır. Başlık veya level 1 metni vurgular. Level 1 metninin ilk satırı hiyerarşinin başlangıcındaki şeklide görünür, sonraki tüm Level 1 satırları uzun dikdörtgenlerin solunda görünür. |
| LinearVenn | 70 | Sıralı olarak üst üste binen ilişkileri göstermek için kullanılır. Yalnızca Level 1 metniyle en iyi çalışır. |
| LinedList | 71 | Metni kategori ve alt kategorilere bölerek büyük miktarda metni göstermek için kullanılır. Birden çok metin seviyesiyle iyi çalışır. Aynı seviyedeki metinler çizgilerle ayrılır. |
| MultidirectionalCycle | 72 | Herhangi bir yönde gerçekleşebilen sürekli bir aşama, görev veya etkinlik dizisini temsil etmek için kullanılır. |
| NameandTitleOrganizationChart | 73 | Bir organizasyonda hiyerarşik bilgi veya raporlama ilişkilerini göstermek için kullanılır. Başlık kutusuna metin girmek için doğrudan daha küçük dikdörtgen şekle yazın. Bu düzenle yardımcı şekil ve Org Chart asılı düzenleri mevcuttur. |
| NestedTarget | 74 | Kapsama ilişkilerini göstermek için kullanılır. Level 1 metninin ilk üç satırı şekillerin sol üst metnine, Level 2 metni ise daha küçük şekillere karşılık gelir. Minimum Level 2 metin satırlarıyla en iyi çalışır. Kullanılmayan metin görünmez, ancak düzenleri değiştirdiğinizde kullanılabilir kalır. |
| NondirectionalCycle | 75 | Aşama, görev veya etkinliklerin döngüsel bir akışta devam eden bir dizisini temsil etmek için kullanılır. Her şeklin aynı önemi vardır. Yönün belirtilmesinin gerekmediği durumlarda iyidir. |
| OpposingArrows | 76 | İki zıt fikri veya merkezi bir noktadan ayrılan fikirleri göstermek için kullanılır. Level 1 metninin ilk iki satırı bir oka karşılık gelir. Kullanılmayan metin görünmez, ancak düzenleri değiştirdiğinizde kullanılabilir kalır. |
| OpposingIdeas | 77 | İki zıt veya karşıt fikri göstermek için kullanılır. Bir veya iki Level 1 öğesi olabilir. Her Level 1 metni birden çok alt seviyeye sahip olabilir. Büyük miktarda metinle iyi çalışır. |
| OrganizationChart | 78 | Bir organizasyonda hiyerarşik bilgi veya raporlama ilişkilerini göstermek için kullanılır. Bu düzenle yardımcı şekil ve Org Chart asılı düzenleri mevcuttur. |
| PhasedProcess | 79 | Bir sürecin üç aşamasını göstermek için kullanılır. Üç Level 1 öğeyle sınırlıdır. İlk iki Level 1 öğe dört Level 2 öğe içerebilir, üçüncü Level 1 öğe ise sınırsız sayıda Level 2 öğe içerebilir. Az miktarda metinle en iyi çalışır. |
| PictureAccentBlocks | 80 | Köşeden başlayan bloklarda bir grup resmi göstermek için kullanılır. İlgili metin dikey olarak görüntülenir. Başlık veya alt başlık slaytlarında vurgu olarak ya da bir belgenin bölüm geçişlerinde iyi çalışır. |
| PictureAccentList | 81 | Gruplanmış veya ilgili bilgiyi göstermek için kullanılır. Üst köşelerdeki küçük şekiller resim barındıracak şekilde tasarlanmıştır. Level 2 metni Level 1 üzerine vurgular ve büyük miktarda Level 2 metni için iyi bir seçimdir. |
| PictureAccentProcess | 82 | Bir görev, süreç veya iş akışındaki sıralı adımları göstermek için kullanılır. Arka plandaki dikdörtgen şekiller resim barındıracak şekilde tasarlanmıştır. |
| PictureCaptionList | 83 | Sırasız veya gruplanmış bilgi bloklarını göstermek için kullanılır. Üst şekiller resim barındıracak şekilde tasarlanmıştır ve resimler metne göre vurgulanır. Kısa metin açıklamalı resimler için iyidir. |
| PictureGrid | 84 | Resimleri kare bir ızgara üzerinde göstermek için kullanılır. Resmin üstünde görünen az miktarda Level 1 metinle en iyidir. |
| PictureLineup | 85 | Yan yana bir dizi resmi göstermek için kullanılır. Level 1 metni resmin üstünü kaplar. Level 2 metni resmin altında görünür. |
| PictureStrips | 86 | Üstten alta bir dizi resmi ve yanlarında Level 1 metnini göstermek için kullanılır. |
| PieProcess | 87 | Bir süreçteki adımları göstermek için kullanılır; her dilim büyüyerek yedi şekle kadar genişler. Level 1 metin dikey olarak görüntülenir. |
| PlusandMinus | 88 | İki fikrin artı ve eksilerini göstermek için kullanılır. Her Level 1 metni birden çok alt seviyeye sahip olabilir. Büyük miktarda metinle iyidir. İki Level 1 öğeyle sınırlıdır. |
| ProcessArrows | 89 | Bir süreç veya iş akışını gösteren bilgiyi göstermek için kullanılır. Level 1 metni dairesel şekillerde, Level 2 metni ok şekillerinde görünür. Minimum metin ve hareket ya da yön vurgulamak için en iyisidir. |
| ProcessList | 90 | Bir görev, süreç veya iş akışındaki bilgi gruplarını veya adım ve alt adımları göstermek için kullanılır. Level 1 metni üst yatay şekillere, Level 2 metni ise her ilgili üst düzey şeklin altındaki dikey alt adımlara karşılık gelir. |
| PyramidList | 91 | Orantılı, birbirine bağlı veya hiyerarşik ilişkileri göstermek için kullanılır. Metin piramit arka planının üzerindeki dikdörtgen şekillerde görünür. |
| RadialCluster | 92 | Merkezi bir fikir veya temaya ilişkin verileri göstermek için kullanılır. Üst Level 1 metni merkezde görünür. Level 2 metni çevredeki şekillerde görünür. En fazla yedi Level 2 şekil içerebilir. Kullanılmayan metin görünmez, ancak düzenleri değiştirdiğinizde kullanılabilir kalır. Az miktarda metinle en iyisidir. |
| RadialCycle | 93 | Merkezi bir fikre olan ilişkiyi göstermek için kullanılır. Ortadaki dairedeki bilgi ve dış halkadaki dairelerin bu fikre nasıl katkıda bulunduğu vurgulanır. İlk Level 1 satırı merkezi daireye, Level 2 metni dış çemberdeki dairelere karşılık gelir. Kullanılmayan metin görünmez, ancak düzenleri değiştirdiğinizde kullanılabilir kalır. |
| RadialList | 94 | Bir döngüde merkezi bir fikre olan ilişkileri göstermek için kullanılır. Ortadaki şekil bir resim içerebilir. Level 1 metni daha küçük dairelerde, ilgili Level 2 metni ise bu dairelerin yanında görünür. |
| RadialVenn | 95 | Üst üste binen ilişkileri ve döngüde merkezi bir fikre olan ilişkiyi göstermek için kullanılır. İlk Level 1 satırı merkezi şekle, Level 2 satırları çevredeki dairesel şekillere karşılık gelir. Kullanılmayan metin görünmez, ancak düzenleri değiştirdiğinizde kullanılabilir kalır. |
| RandomToResultProcess | 96 | Bir dizi adım aracılığıyla birkaç kaotik fikrin nasıl birleşik bir hedefe ya da fikre dönüşebileceğini göstermek için kullanılır. Birden çok Level 1 metin öğesini destekler, ancak ilk ve son Level 1 şekilleri sabittir. Az miktarda Level 1 metin ve orta miktarda Level 2 metinle en iyisidir. |
| RepeatingBendingProcess | 97 | Bir görev, süreç veya iş akışındaki ilerlemeyi veya sıralı adımları göstermek için kullanılır. Şekiller için hem yatay hem de dikey gösterim alanını maksimize eder. |
| ReverseList | 98 | İki öğe arasında geçiş yapmak için kullanılır. Sadece ilk iki metin öğesi görüntülenir ve her öğe büyük miktarda metin içerebilir. İki öğe arasındaki değişikliği veya sıra kaymasını göstermek için iyidir. |
| SegmentedCycle | 99 | Dairesel bir akışta aşama, görev veya etkinlik dizisini göstermek için kullanılır. Birbirine bağlı parçalar vurgulanır. Level 1 metninin ilk yedi satırı bir dilim ya da pasta şekline karşılık gelir. Kullanılmayan metin görünmez, ancak düzenleri değiştirdiğinizde kullanılabilir kalır. |
| SegmentedProcess | 100 | Bir görev, süreç veya iş akışındaki ilerlemeyi veya sıralı adımları göstermek için kullanılır. Her satır ayrı bir şekle geldiğinden Level 2 metni vurgulanır. |
| SegmentedPyramid | 101 | Kapsama, orantılı veya birbirine bağlı ilişkileri göstermek için kullanılır. Level 1 metninin ilk dokuz satırı üçgen şekillerde görünür. Kullanılmayan metin görünmez, ancak düzenleri değiştirdiğinizde kullanılabilir kalır. Yalnızca Level 1 metniyle en iyisidir. |
| SnapshotPictureList | 102 | Açıklayıcı metinle birlikte resimleri göstermek için kullanılır. Level 2 metni bilgi listeleri içerebilir. Büyük miktarda metinle iyi çalışır. |
| SpiralPicture | 103 | Merkeze doğru spiralli bir şekilde, eşleşen Level 1 başlıklarıyla beşe kadar resim serisini göstermek için kullanılır. |
| SquareAccentList | 104 | Bilgiyi kategorilere bölünmüş listeler halinde göstermek için kullanılır. Level 2 metni küçük bir kare şeklin yanında görünür. Büyük miktarda Level 2 metniyle iyidir. |
| StackedList | 105 | Bilgi gruplarını veya bir görev, süreç ya da iş akışındaki adımları göstermek için kullanılır. Dairesel şekiller Level 1 metni, ilgili dikdörtgenler Level 2 metni içerir. Çok detay ve az Level 1 metni için iyidir. |
| StackedVenn | 106 | Üst üste binen ilişkileri göstermek için kullanılır. Büyümeyi veya derecelendirmeyi vurgulamak için iyi bir seçimdir. Yalnızca Level 1 metniyle en iyisidir. Level 1 metninin ilk yedi satırı bir dairesel şekle karşılık gelir. Kullanılmayan metin görünmez, ancak düzenleri değiştirdiğinizde kullanılabilir kalır. |
| StaggeredProcess | 107 | Aşamalar boyunca aşağı yönlü bir ilerlemeyi göstermek için kullanılır. Seviye 1 metninin ilk beş satırı bir dikdörtgenle eşleşir. Kullanılmayan metin görünmez, ancak düzenleri değiştirdiğinizde hâlâ kullanılabilir. |
| StepDownProcess | 108 | Birden fazla adım ve alt adım içeren aşağı doğru bir süreci göstermek için kullanılır. Az miktarda metinle en iyi çalışır. |
| StepUpProcess | 109 | Yukarı doğru bir adım serisini veya bilgi listelerini göstermek için kullanılır. |
| SubStepProcess | 110 | Seviye 1 metninin her örneği arasında alt adımlar bulunan çok adımlı bir süreci göstermek için kullanılır. Az miktarda metinle en iyi çalışır ve yedi Seviye 1 adımıyla sınırlıdır. Her Seviye 1 adımı sınırsız sayıda alt adım içerebilir. |
| TableHierarchy | 111 | Üstten alta inen bilgi gruplarını ve her grup içindeki hiyerarşileri göstermek için kullanılır. Bu düzen bağlayıcı çizgiler içermez. |
| TableList | 112 | Eş değerli gruplandırılmış veya ilgili bilgileri göstermek için kullanılır. İlk Seviye 1 metin satırı üst şekille eşleşir ve onun Seviye 2 metni sonraki listeler için kullanılır. |
| TargetList | 113 | Birbirine ilişkili veya üst üste gelen bilgileri göstermek için kullanılır. Seviye 1 metninin ilk yedi satırı dikdörtgen şekil içinde görünür. Kullanılmayan metin görünmez, ancak düzenleri değiştirdiğinizde hâlâ kullanılabilir. Hem Seviye 1 hem de Seviye 2 metinle iyi çalışır. |
| TextCycle | 114 | Aşama, görev veya olayların dairesel bir akışta devam eden bir dizisini temsil etmek için kullanılır. Aşamalar ya da adımlardan ziyade okları veya akışı vurgular. Yalnızca Seviye 1 metniyle en iyi çalışır. |
| TitlePictureLineup | 115 | Her biri kendi başlığı ve açıklaması olan bir dizi resmi göstermek için kullanılır. Seviye 1 metni resmin üzerindeki kutuda görünür. Seviye 2 metni resmin altında görünür. |
| TitledMatrix | 116 | Dört bölmenin bütünle ilişkisini göstermek için kullanılır. İlk Seviye 1 metin satırı merkezi şekille eşleşir ve ilk dört Seviye 2 metin satırı bölmelerde görünür. Kullanılmayan metin görünmez, ancak düzenleri değiştirdiğinizde hâlâ kullanılabilir. |
| TitledPictureAccentList | 117 | Her Seviye 2 metni için vurgu resmi içeren bilgi listelerini göstermek için kullanılır. Seviye 1 metni listenin üst kısmındaki ayrı bir kutuda görüntülenir. |
| TitledPictureBlocks | 118 | Bir dizi resmi göstermek için kullanılır. Seviye 1 metni her resmin üzerinde görünür. Seviye 2 metni ise yan tarafta ve hafifçe resimlerin üzerine gelecek şekilde görünür. |
| TrapezoidList | 119 | Eş değerli gruplandırılmış veya ilgili bilgileri göstermek için kullanılır. Büyük miktarda metinle iyi çalışır. |
| UpwardArrow | 120 | Bir görev, süreç veya iş akışında yukarı yönlü bir ilerleme veya adımları göstermek için kullanılır. Seviye 1 metninin ilk beş satırı ok üzerindeki bir nokta ile eşleşir. Minimum metinle en iyi çalışır. Kullanılmayan metin görünmez, ancak düzenleri değiştirdiğinizde hâlâ kullanılabilir. |
| VerticalAccentList | 121 | Bilgi listelerini göstermek için kullanılır. Seviye 2 metni dikey şeritlerin üzerine dikdörtgen şekillerde görünür. Seviye 2 metni Seviye 1 metnine göre vurgulanır ve orta miktarda Seviye 2 metni için iyi bir seçimdir. |
| VerticalArrowList | 122 | Ortak bir hedefe doğru ilerleyen bir görev, süreç veya iş akışı içindeki aşama veya sıralı adımları göstermek için kullanılır. Madde işaretli bilgi listeleri için iyi çalışır. |
| VerticalBendingProcess | 123 | Bir görev, süreç veya iş akışındaki ilerleme veya sıralı adımları göstermek için kullanılır. Şekiller için hem yatay hem de dikey görüntü alanını maksimize eder. Yön veya hareketten ziyade şekiller arasındaki ilişkileri daha çok vurgular. |
| VerticalBlockList | 124 | Bir görev, süreç veya iş akışındaki bilgi gruplarını veya adımları göstermek için kullanılır. Büyük miktarda Seviye 2 metniyle iyi çalışır. Ana noktası ve birden fazla alt noktası olan metinler için iyi bir seçimdir. |
| VerticalBoxList | 125 | Özellikle büyük miktarda Seviye 2 metni içeren birden çok bilgi grubunu göstermek için kullanılır. Madde işaretli bilgi listeleri için iyi bir seçimdir. |
| VerticalBulletList | 126 | Sırasız veya gruplandırılmış bilgi bloklarını göstermek için kullanılır. Uzun başlıklar veya üst seviye bilgiler içeren listeler için iyi çalışır. |
| VerticalChevronList | 127 | Bir görev, süreç veya iş akışındaki ilerleme veya sıralı adımları, ya da hareketi/yönü vurgulamak için kullanılır. Seviye 2 metni Seviye 1 metnine göre vurgulanır ve büyük miktarda Seviye 2 metni için iyi bir seçimdir. |
| VerticalCircleList | 128 | Sıralı ya da gruplandırılmış verileri göstermek için kullanılır. Büyük bir dairesel şeklin yanında görünen Seviye 1 metniyle en iyi çalışır. Alt seviye metinler daha küçük dairesel şekillerle ayrılır. |
| VerticalCurvedList | 129 | Eğri bir bilgi listesi göstermek için kullanılır. Vurgu daire şekillerine resim eklemek için resim dolgusu uygulayın. |
| VerticalEquation | 130 | Bir plan veya sonucu gösteren sıralı adım veya görevleri göstermek için kullanılır. Son Seviye 1 metin satırı ok sonrası görünür. Yalnızca Seviye 1 metniyle en iyi çalışır. |
| VerticalPictureAccentList | 131 | Sırasız veya gruplandırılmış bilgi bloklarını göstermek için kullanılır. Küçük daireler resim içerecek şekilde tasarlanmıştır. |
| VerticalPictureList | 132 | Sırasız veya gruplandırılmış bilgi bloklarını göstermek için kullanılır. Soldaki küçük şekiller resim içerecek şekilde tasarlanmıştır. |
| VerticalProcess | 133 | Bir görev, süreç ya da iş akışında yukarıdan aşağıya doğru ilerleme veya sıralı adımları göstermek için kullanılır. Dikey alan sınırlı olduğundan yalnızca Seviye 1 metniyle en iyi çalışır. |
| Custom | 134 | Özel düzen şablonlu bir [SmartArt](../smartart/) diyagramını temsil eder |
| PictureOrganizationChart | 135 | Bir organizasyonda hiyerarşik bilgi veya raporlama ilişkilerini, ilgili resimlerle göstermek için kullanılır. Bu düzenle asistan şekli ve Org Chart asılı düzenleri mevcuttur. |

## Bakınız

* Ad Alanı [Aspose::Slides::SmartArt](../)
* Kütüphane [Aspose.Slides](../../)