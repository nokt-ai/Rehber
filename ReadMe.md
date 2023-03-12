# Midjourney İçin Faydalı Promptlar
Giriş
Hazırladığımız rehber, yazı karşılığında resim çizen yapay zeka Midjourney için başlangıç seviyesinde 

[Deneme Görseli] (https://cdn.discordapp.com/attachments/1016026195072135198/1084516511680569445/Jinglemisk_Oil_Painting_Ancient_Egpyt_Nile_River_barges_fisherm_21274377-1757-49e5-8c14-f50c85a51f90.png)



Bu kılavuz, temel ve orta seviye ipuçlarını kapsayacak ve sizi Midjourney'de ipucu yazmaya yaklaşma adımlarına götürecektir. Midjourney bot, yazma becerilerinizi geliştirmek için mükemmel bir başlangıç noktası olabilir, özellikle de ipucu yazmaya yaklaşmak söz konusu olduğunda. Çok yönlü bir araç olarak, ipucu yazma pratiği yapmak, geri bildirim almak ve yazma stilinizi geliştirmek için bir platform sağlar. Ayrıca, ister deneyimli bir yazar olun ister yeni başlıyor olun, genel olarak yazma ipuçlarına yaklaşmak için bir basamak görevi görebilir. Kendinizden emin bir şekilde yazmanıza ve becerilerinizi geliştirmenize yardımcı olmak için çok sayıda örnek sunulacaktır.
Dil Engelini Aşmak
Yapay zekaların çoğunluğu kendilerine Türkçe verilen prompt’ları anlamakta pek güçlük çekmeyip, çoğu zaman da zorlanmadan Türkçe cevap verebilmektedirler. ChatGPT, Midjourney gibi en sık kullanılan yapay zekalar her ne kadar bu koşulları karşılayabilseler de kavrayışlarının eksik, Türkçelerinin de hantal ve gündelik konuşma dilinden uzak olduğunu görüyoruz. Beslendiği kaynakların ağırlığı Türkçe olmayan her yapay zeka, aynı sorunu yaşayacaktır. 

Midjourney Türkçe promptları pekala kabul eder, çoğunlukla da ne kast edildiğini aşağı yukarı doğru tahmin etmiş olur. Ancak hem birçok kelimeyi doğru anlayamaz, hem de kavrayış eksikliğini önyargılı davranarak telafi etmeye çalışır. İngilizce her kelimeyi anladığı için bir kavrayış eksikliği yaşamaz. Bu yüzden de bir prompt yeteri kadar detaylıysa, asla özellikle İngiliz ve Amerikan kültüründen beslenmez. Gelgelelim, Midjourney kendisine verilen her Türkçe kelimeyi anlayamadığı, ve kendisine Türkçe, Türkiye hakkında verilen örnekler eksik kaldığı için çok basit bir prompt’ta bile sorun çıkartabiliyor. Sizin için birkaç örnek hazırladık.


Prompt: Çay içen yaşlı kadın, balkon, apartman, gökyüzü, detaylı, gerçekçi, fotoğrafik
Prompt: Old woman drinking tea, balcony, apartment, sky, detailed,
realistic, photographic















Burada dikkat çeken iki unsur var. Birincisi, Türkçe verilen prompt’ta özellikle “yaşlı” dememize rağmen hiç yaşlı bir kadın görmüyor olmamız. Oysa ki İngilizce halinde dört denemede de yaşlı bir kadın olduğunu görüyoruz. İkinci unsur ise, ki duruma göre bu faydalı dahi olacak bir özelliktir, Türkçe verilen prompt’lara Midjourney’nin özellikle Türkiye’den esinlenerek bir estetik kurgulamasıdır. Soldaki fotoğrafta bulunan evler Türkiye’yi anımsatıyor, öyle ki bir tanesinde İstanbul Boğazı’nı görmek bile mümkün. 


Prompt: Modern iş adamı, sokaklar, kalabalıklar
Prompt: Modern businessman, streets, crowds









Türkçe halinde bir “iş adamı”nı bile kavrayamadı, bunun yerine sokaklara odaklandı ve serbest bir çağrışımda bulunup kasaba evleri çizdi. Buradaki bir istisna, sol üstte yer alan ve göl, dağlar, tekne gibi prompt’tan alakasız nesneler içeren deneme. Midjourney, sanki bir film ya da albüm kapağı tasarlar gibi bir başlık atmaya bile çalışmış. Bu, İngilizce dışında bir dil kullanırken olağandışı bir olay değil. Biraz daha incelersek:

Prompt: kravatlı adam, sokaklar, 
kalabalık
Prompt: modern şirket çalışanı, sokaklar, kalabalık













İstediğimiz sonuçtan giderek uzaklaşıyoruz. Midjourney de kavrayışının el vermediği noktalarda giderek emin olduğu şeyler üzerine yoğunlaşıp, prompt’un geneline karşı tepkisiz hale geliyor. Sol yukarıdaki prompt için sadece ikisinde bir “adam” çiziyor, bunlardan birini ucundan “Türk” olarak yorumluyor. Hepsinin altında (muhtemelen Midjourney’e verilen örneklerin çoğunluğunu oluşturan) posterlerden, albüm kapaklarından, reklamlardan esinlenilmiş başlık niteliğinde yazılar görülüyor. Prompt’u biraz daha detaylandırdığımızda işler çığırından çıkıyor:


Prompt: Sahil kasabası, festival, akdeniz, açık hava, günbatımı, realistik, detaylı, fotorealistik, 35mm lens --ar 3:2 --chaos 65
Prompt: beach town, festival, Mediterranean, clear sky, sunset, realistic, detailed, photorealistic, 35mm lens --ar 3:2 --chaos 65
















Bu noktada yapılabilecek en faydalı şey, eğer prompt’ları istediğimiz biçimde İngilizce’de düşünmekte zorlanıyorsak, DeepL gibi bir tercüman kullanarak istediklerimizi Midjourney’e aktarabiliriz. Bu rehberde aktarmaya çalıştığımız prompt yazım mantığına uyulduğu takdirde, Midjourney kendisine veirlen Türkçe’den çevrilmiş İngilizce prompt’ları yorumlamakta güçlük çekmeyecek, ve kuvvetli ihtimalle başarılı olacaktır. 

Başlangıç
<< bu işaretin >> içinde verilen tüm prompt’lar tek başlarına alınmalı, “<< >>” sembolleri alıntıdan çıkartılmalıdır.

Midjourney ve Discord Üyeliği

Temel Kavramlar
/imagine, /info, URL, /blend

/imagine
Midjourney’de her prompt, satıra Tüm prompt’lar << /imagine >> yazarak başlar. Discord, bunu yazıp bir boşluk bıraktığınız anda bunu şöyle tamamlar:









“Prompt” kelimesinin içinde bulunduğu kutucuğa yazdığımız her şey, Midjourney tarafından prompt olarak kabul edilir ve yorumlamaya dahil olur. Süreç şöyle özetlenebilir:

<< /imagine >> yazılır ve boşluk tuşuna basılır
İstenilen prompt yazılır: Örneğin: << Dogs running by the beach, ocean, ships >>
Enter’a basılır.


/info
Eğer “fast” (hızlı) modu kullanıyorsanız, Midjourney prompt’a vereceği cevabı en fazla 60 saniye içerisinde oluşturur. Şayet “relax” (rahat) modu kullanıyorsanız, bu Midjourney yoğunluğuna göre daha uzun sürebilir. << /fast >> ve << /slow >> yazarak modu değiştirebilir, << /info >> ile de kullanım süreniz gibi hesap detaylarına ulaşabilirsiniz.




/blend
URL

Arayüz
Midjourney, kendisine verdiğimiz her prompt için dört farklı görsel oluşturur. Bize cevap verdiğinde cevabının şöyle bir formatı olacaktır:

 U1   U2   U3   U4  (“Upscaling”):

Numaralandırılmış görselin çözünürlüğünü arttırır. Beğendiğimiz bir görseli kaydetmeden evvel Upscaling uygulamak tavsiye edilir.

 V1   V2   V3   V4  (“Variation”):

Numaralandırılmış görselin bir varyantını alır. Eğer yorumlamalardan bir tanesini özellikle beğendiyseniz varyant aldığınızda elde edeceğiniz dört yeni görsel, burada seçtiğiniz görsele tarz ve içerik olarak yakından benzeyecektir.


Prompt: Exploring the deep space, Kandinsky style painting, black hole, photon beams, relativity --v 1 ( “Uzayın derinliklerini keşfetmek, Kandinsky tarzı resim, kara delik, foton ışınları, izafiyet --v 1” )

Son olarak şayet hiçbir yorumlamadan memnun kalmadıysak, sağ alttaki 🔁 tuşuna bastığımızda bize aynı prompt’u baştan yorumlayacak ve dört yeni görsel sunacaktır.

Midjourney’de aklımızdaki görsele en yakın yorumlamaya ulaşmak için, yazdığımız prompt’larda değişiklik yaptığımız kadar varyant almamız gerekebiliyor. Midjourney’in bize sunduğu dört yorumlamadan sonra prompt değişikliği ve varyantlar üzerinden paralel aramalar yürütmüş oluyoruz. Örneğin bir varyant daha soyut ve estetik bir yorumlama üzerinden gidiyor, başka bir varyantı ise belki de çok istediğimiz bir detayı yakaladığı için elimizde tutuyor, varyant alarak da diğer detayları tamamlamasını umuyoruz.

<< /relax >> komutunun en büyük faydası da burada ortaya çıkıyor. Eğer acelemiz yoksa, ve bolca aramayı paralelde yürütüp elde ettiğimiz yorumlamaları detaylı incelemek istiyorsak, << /relax >> modda çalışıp biraz vakitten fedakarlık edip fotoğraf üretme hakkımızdan kazanıyoruz. Özellikle de başka bir iş ile meşgulsek, bu modda çalışıp örneğin beş dakikada bir Midjourney’e bakmak süreci keyifli olduğu kadar verimli hale getirebiliyor.

Elimizdeki sorgular biriktiğine göre, çözünürlük arttırmak ve son rötuşları atmak hakkında bilgi sahibi olabiliriz.
Çözünürlük Ayarları
İleri Çözünürlük Arayüzü
Herhangi bir fotoğraf için Upscaling yaptığımızda, örneğin  U2  tuşuna bastığımızda, Midjourney bize yine moda göre 60 saniye, ya da daha uzun bir süre sonra, istediğimiz görselin daha yüksek çözünürlükteki bir halini verecektir. Yeni görselimizde yeni birkaç seçenek eklenir.



















Prompt: Ancient Egypt, wide view of the Nile River, barges on the river, fishermen, Nile coastline, desert haze, oil painting, desert vegetation --ar 16:9 ( “Antik Mısır, Nil Nehri'nin geniş görünümü, nehirdeki mavnalar, balıkçılar, Nil kıyı şeridi, çöl pusu, yağlı boya, çöl bitki örtüsü --ar 16:9” )

Make Variations: Görselin şu anki halinin varyantını alır ve dört yeni görsel oluşturur,   V3  gibi V-tipi tuşlarla aynı mantıkta çalışır. 

Beğendiğimiz bir yorumlamayı çeşitlendirmek için varyant almadan evvel sabretmek daha akıllıca olabilir. Eğer bu görselin detaylarını çeşitlendirirsek, ve bu halinin varyantlarını alırsak, o halde Midjourney istediğimiz yorumlamaya daha çabuk bile ulaşabilir. 
Light & Detailed Upscale
Light Upscale Redo, Görselin çözünürlüğünü yükseltmeden, ebatı aynı bırakarak detaylarını çeşitlendirir (Beta Upscale Redo’nun tam tersi gibi işler). Bu seçeneğe tıkladığımızda karşımıza yeni bir seçenek daha çıkar:

















Detailed Upscale Redo: Light Upscale Redo ile detaylandırılmış bir görselin çözünürlüğünü de yükseltir.
Beta Upscale
Beta Upscale Redo: Görselin detaylarını çeşitlendirmeden çözünürlüğünü yükseltir (Light 
Upscale Redo’nun tam tersi gibi işler).

Remaster
Midjourney’in test sürümlerine başvurarak fotoğrafı tekrar yorumlar. 

























Remaster’ladığımız görsel aslında ana içerik olarak yukarıdaki yorumlamalarla çok benzeşiyor. Fakat “içerik” diye yorumladıklarımız, yani gemi, balıkçılar, nehir, çöl havası gibi nesnelere farklı bir dokunuş getiriliyor. 

Sonuçların Karşılaştırılması
















Başlangıç

















Light Upscale Redo






















Detailed Upscale Redo



















Beta Upscale Redo
























Beta - Remaster




















Detailed - Remaster


Midjourney’de aynı görsel üzerinden saatler boyu farklı yorumlamalar türetilebilir. Başlangıçta hiç aklımızda olmayan bir estetik dokunuşu Midjourney kendi denemelerinden birinde bize sunabilir. 

