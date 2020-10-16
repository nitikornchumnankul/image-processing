# image-processing
การสร้างเครื่องมือที่จะตรวจจับความผิดปกติของเซลล์ที่ก่อให้เกิดมะเร็งจากภาพถ่าย

เป้าหมายเดียวกันแต่ใช้เทคโนโลยีที่ถูกพัฒนาโดยกลุ่มคนต่างกันฉะนั้นจึงถือเป็นลิขสิทธิ์ทางปัญญาและเทคโนโลยีของใครของมัน

image processing เพื่อ การจำแนก
เพราะขั้นตอนแรกคือ
1. ต้องออกช้อปปิ้งหาไอเดียจากหลายๆที่ให้ได้มากที่สุด
2. โดยกำหนดกลุ่มเป้าหมายให้ชัดเจนแล้วไปดูว่ามีใครบ้างทำอะไรบ้างโดยวิธีใดบ้างได้ผลอย่างไรบ้าง
3. อาจจะเริ่มที่ส่วนที่รู้สึกว่าถนัดและรู้สึกสนใจก่อนก็ได้นะครับ
4. dataset ใน github เรื่องนี้มีส่วนไหนบ้าง ที่เกี่ยวข้องกับมะเร็งเต้านม
5. เจาะโครงสร้างของสักบริบัท เขาวางหน่วยวางทีมอะไรบ้าง 

## มะเร็งเต้านม
[มะเร็งเต้านมมะเร็งอันดับ 1 ของผู้หญิง](https://www.sikarin.com/content/detail/461/%E0%B9%82%E0%B8%A3%E0%B8%84%E0%B8%A1%E0%B8%B0%E0%B9%80%E0%B8%A3%E0%B9%87%E0%B8%87%E0%B9%80%E0%B8%95%E0%B9%89%E0%B8%B2%E0%B8%99%E0%B8%A1-%E0%B8%A1%E0%B8%B0%E0%B9%80%E0%B8%A3%E0%B9%87%E0%B8%87%E0%B8%AD%E0%B8%B1%E0%B8%99%E0%B8%94%E0%B8%B1%E0%B8%9A-1-%E0%B8%82%E0%B8%AD%E0%B8%87%E0%B8%9C%E0%B8%B9%E0%B9%89%E0%B8%AB%E0%B8%8D%E0%B8%B4%E0%B8%87)

[6 สัญญาณเตือนมะเร็งเต้านม](https://www.samitivejhospitals.com/th/%E0%B8%AA%E0%B8%B1%E0%B8%8D%E0%B8%8D%E0%B8%B2%E0%B8%93%E0%B8%A1%E0%B8%B0%E0%B9%80%E0%B8%A3%E0%B9%87%E0%B8%87%E0%B9%80%E0%B8%95%E0%B9%89%E0%B8%B2%E0%B8%99%E0%B8%A1/)

[คู่มือ การตรวจเต้านมโดยบุคลากรทางแพทย์ Clinical Breast Examination:CBE](http://www.nci.go.th/th/File_download/D_index/CBE/%E0%B8%84%E0%B8%B9%E0%B9%88%E0%B8%A1%E0%B8%B7%E0%B8%AD%20%E0%B8%81%E0%B8%B2%E0%B8%A3%E0%B8%95%E0%B8%A3%E0%B8%A7%E0%B8%88%E0%B9%80%E0%B8%95%E0%B9%89%E0%B8%B2%E0%B8%99%E0%B8%A1.pdf)

[คู่มือการตรวจคัดกรองมะเร็งเต้านม](http://www.kaengkrachan-hospital.com/images/main_1550108300/%E0%B8%84%E0%B8%B9%E0%B9%88%E0%B8%A1%E0%B8%B7%E0%B8%AD%E0%B8%81%E0%B8%B2%E0%B8%A3%E0%B8%95%E0%B8%A3%E0%B8%A7%E0%B8%88%E0%B8%84%E0%B8%B1%E0%B8%94%E0%B8%81%E0%B8%A3%E0%B8%AD%E0%B8%87%E0%B8%A1%E0%B8%B0%E0%B9%80%E0%B8%A3%E0%B9%87%E0%B8%87%E0%B9%80%E0%B8%95%E0%B9%89%E0%B8%B2%E0%B8%99%E0%B8%A1.pdf)

[การตรวจแมมโมแกรม / การตรวจเอกซเรย์เต้านม (Mammogram)](https://medthai.com/%E0%B8%81%E0%B8%B2%E0%B8%A3%E0%B8%95%E0%B8%A3%E0%B8%A7%E0%B8%88%E0%B9%81%E0%B8%A1%E0%B8%A1%E0%B9%82%E0%B8%A1%E0%B9%81%E0%B8%81%E0%B8%A3%E0%B8%A1/)

[แมมโมแกรม ตรวจเร็ว แม่นยำ ปลอดภัย](https://www.siphhospital.com/th/news/article/share/515)
## [breast-cancer-prediction](https://github.com/topics/breast-cancer-prediction)

## DATASETS
[Breast Cancer Classification SVM](https://www.kaggle.com/babakgohardani/breast-cancer-classification-svm)

[Breast cancer classification with Keras and Deep Learning](https://www.pyimagesearch.com/2019/02/18/breast-cancer-classification-with-keras-and-deep-learning/)

[NYU open-sources breast cancer screening model trained on over 200,000 mammography exams](https://venturebeat.com/2019/03/21/nyu-open-sources-breast-cancer-screening-model-trained-on-over-200000-mammography-exams/)
## Search

[OpenML](https://www.openml.org/search?type=data)

[Dataset Search](https://datasetsearch.research.google.com/)

## Niramai Company
[interview ceo](https://blogs.cisco.com/csr/women-rock-it-geetha-manjunath-niramai#:~:text=Corporate%20Social%20Responsibility-,The%20Founder%2C%20CEO%20and%20CTO%20of%20Niramai%20on,Early%20Detection%20of%20Breast%20Cancer&text=Dr.,and%20why%20she%20founded%20Niramai.)

[Network of Niramai Health Analytix](https://www.tofler.in/niramai-health-analytix-private-limited/company/U72200KA2016PTC095020/network)

[niramai](https://www.niramai.com/)

[youtube](https://www.youtube.com/playlist?list=PL25iL2iPp9_bzVZlU3Qxn8tdsUdvtnwU9)

[twitter](https://twitter.com/niramaianalytix)

[founding rounds](https://www.crunchbase.com/organization/niramai-health-analytix/company_financials)

[SMILE Tool](https://www.niramai.com/about/smile/)

[Geetha Manjunath, Research Gate](https://www.researchgate.net/profile/Geetha_Manjunath)


## Camera
[Camera](https://termogram.com/)

[Human-Body Temperature Checking Infrared Thermal Camera](https://johotek01.en.made-in-china.com/productimage/UMAnTxOVHwpZ-2f1j00OsvQFCnbwErm/China-Human-Body-Temperature-Checking-Infrared-Thermal-Camera.html)

## News
[Mum’s breast cancer spotted by museum’s thermal imaging camera](https://metro.co.uk/2019/10/22/mums-breast-cancer-spotted-museums-thermal-imaging-camera-10963552/)

## Research
[Breast Cancer Detection in Mammograms using Deep Neural Networks](https://www.researchgate.net/publication/337674033_Breast_Cancer_Detection_in_Mammograms_using_Deep_Neural_Networks)

[MaskMitosis: a deep learning framework for fully supervised, weakly supervised, and unsupervised mitosis detection in histopathology images](https://link.springer.com/article/10.1007/s11517-020-02175-z)

[Deep Neural Networks Improve Radiologists’Performance in Breast Cancer Screening](https://arxiv.org/pdf/1903.08297.pdf)

[***Breast Cancer Detection Using Infrared Thermal Imaging and a Deep Learning Model](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.mdpi.com%2F1424-8220%2F18%2F9%2F2799%2Fpdf-vor&psig=AOvVaw1iWGeLE5tbMzdv644WE1VM&ust=1602867002643000&source=images&cd=vfe&ved=0CA0QjhxqFwoTCIDOsYaHt-wCFQAAAAAdAAAAABAj)

[Basic Information About Breast Cancer](https://www.cdc.gov/cancer/breast/basic_info/index.htm)

## Temperature Detection
[Temperature Matters! And Why it Should Matter to Tumor Immunologists](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3904378/X)
![](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3904378/bin/nihms544172f1.jpg)

# References

[Detecting cancer in real-time with machine learning](https://www.youtube.com/watch?v=9Mz84cwVmS0&feature=share&fbclid=IwAR3Xl5jGYSsASg9WuezoGyJesUo_yWi1L-YRIXdKxhXYzynUidsYxM9l97s)

[AI model improves breast cancer detection on mammograms](https://www.youtube.com/watch?v=Mur70YjInmI&feature=share&fbclid=IwAR2xJUBHEjRPsjBs5CLwclsC2S5meCvL_r_-326Xoz0FcNEN4hqg0U)
