# Adaptive Method For Multi Colored Text Binarization

paper source:
- https://www.researchgate.net/publication/318123092_Adaptive_method_for_multi_colored_text_binarization
- http://www.m.cs.osakafu-u.ac.jp/cbdar2007/proceedings/papers/O1-1.pdf

note:
implementation differs from the papers
- Canny threshold 100, 100
- Discard edge box area < 4 (paper 15)
- Discard edge box width / height > 5 (paper 10)
- Inner edge box counted when area >= 20
- Point 5 using K = 5 (paper 20), accepts large text

<div>
<img src="https://github.com/tiok-cek1/text-binarization/raw/master/sample/img1.png" height=100 style="float:left" />
<img src="https://github.com/tiok-cek1/text-binarization/raw/master/sample/img1_result.png" height=100 />
</div>

<div>
<img src="https://github.com/tiok-cek1/text-binarization/raw/master/sample/img2.png" height=100 style="float:left" />
<img src="https://github.com/tiok-cek1/text-binarization/raw/master/sample/img2_result.png" height=100 />
</div>

<div>
<img src="https://github.com/tiok-cek1/text-binarization/raw/master/sample/img3.png" height=100 style="float:left" />
<img src="https://github.com/tiok-cek1/text-binarization/raw/master/sample/img3_result.png" height=100 />
</div>

<div>
<img src="https://github.com/tiok-cek1/text-binarization/raw/master/sample/bigtext.jpg" height=100 style="float:left" />
<img src="https://github.com/tiok-cek1/text-binarization/raw/master/sample/bigtext_result.png" height=100 />
</div>

<div>
<img src="https://github.com/tiok-cek1/text-binarization/raw/master/sample/tips.jpg" height=100 style="float:left" />
<img src="https://github.com/tiok-cek1/text-binarization/raw/master/sample/tips_result.png "height=100 />
</div>
