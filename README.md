# goruntu_isleme_projesi


--------------Proje Sahipleri---------------
Necati Çuhadar,
Seyit Dağ,
Ramazan Kayalı,

Proje bağımlılıkları requirements.txt dosyası içerisinde listelenmiştir. Bağımlılıkları indirmek için CMD ile dosyanın bulunduğu dizine geçerek "pip install -r requirements.txt" komutunu girmeniz gerekmektedir. Daha sonra pip, bağımlılıkları indirecektir.

Proje dosyaları içerisinde veriseti de bulunmaktadır ve bu verisetini Masaüstünde Veriseti isminde bir klasör oluşturup içerisine taşımanız gerekmektedir.
Ayrıca isterseniz kendi verisetinizi de oluşturabilirsiniz. Bunun için masaüstünde Resimler isimli klasör oluşturup içerisine de ayrı ayrı motor ve bisiklet isimli klasörler ekleyerek her klasör için ilgili resim dosyasını klasör içine koyabilirsiniz (motorları motor klasörü, bisikletleri bisiklet klasörü içine koyun) ve ardından main.ipynb Jupyter notebook dosyası içindeki ilk hücreyi çalıştırın. Bu sayede Resimler içerisindeki her bir resimden 20 farklı kopya oluşturulacak ve sonrasında her bir kopyaya belirlediğimiz 5 efektten bir tanesi uygulanacaktır.
Ardından oluşturulan tüm resimlerin %70'i test ve %30'u validation seti için ayrılarak Veriseti klasörü içerisinde ilgili yerlere taşınacaktır. Ardından Resimler klasörünü silebilirsiniz.
Verisetini kendiniz oluşturmak istemiyorsanız main.ipynb dosyası içerisindeki birinci hücreyi çalıştırmayınız.

Eğitimin ardından test yapmak isterseniz, test verilerinizi Masaüstü > Veriseti > test klasörü içerisine koyabilir ve main.ipynb içerisindeki son hücreyi çalıştırabilirsiniz.


Ayrıca consts.py dosyası içerisindeki resim_yolu değişkeninin değerini değiştirerek kopya oluşturup efekt uygulanacak olan resimlerin tutulduğu klasör dizinini, veriseti_yolu değişkeni ile verisetinin ana dizinini, egitim_yolu değişkeni ile eğitim setinin yolunu, validation_yolu değişkeni ile validation setinin yolunu, test_yolu ile test setinin yolunu değiştirebilirsiniz.
