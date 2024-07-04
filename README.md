# Loan Prediction Analysis
 
     Giriş
     
     Bu proje, bir bankanın kredi başvurularına ilişkin verilerin analiz edilmesi, temizlenmesi ve modellenmesini amaçlamaktadır. Proje kapsamında, kredi başvurularının onaylanıp onaylanmadığını tahmin etmek için farklı sınıflandırma algoritmaları kullanılarak modeller oluşturuldu. Bunun yanında, kredi miktarının tahmin edilmesi için de regresyon algoritmaları değerlendirildi. Projenin amacı, bankanın kredi onay süreçlerini daha iyi anlamasına ve karar verme süreçlerini optimize etmesine yardımcı olmaktır.
     
     Veri Seti Hakkında
     Bu projede kullanılan veri seti, 614 kredi başvurusuna ait bilgiler içermektedir. Veri seti, başvuru sahiplerinin demografik bilgileri, gelir düzeyleri, kredi geçmişleri ve başvurulan kredi miktarları gibi çeşitli özellikleri içermektedir. Bu özellikler, kredi başvurularının onaylanma durumu ile ilişkilendirilecektir.
     Veri seti şu sütunları içermektedir:
1.	Loan_ID: Kredi başvuru ID'si
2.	Gender: Başvuru sahibinin cinsiyeti
3.	Married: Başvuru sahibinin evli olup olmadığı
4.	Dependents: Başvuru sahibinin bakmakla yükümlü olduğu kişi sayısı
5.	Education: Başvuru sahibinin eğitim durumu (Mezun veya Mezun değil)
6.	Self_Employed: Başvuru sahibinin kendi işinde çalışıp çalışmadığı
7.	ApplicantIncome: Başvuru sahibinin geliri
8.	CoapplicantIncome: Eş başvuru sahibinin geliri
9.	LoanAmount: Başvurulan kredi miktarı
10.	Loan_Amount_Term: Kredi vadesi (ay olarak)
11.	Credit_History: Kredi geçmişi (1: iyi, 0: kötü)
12.	Property_Area: Başvuru sahibinin mülk alanı (Kentsel, Yarı kentsel, Kırsal)
13.	Loan_Status: Kredi başvurusunun onaylanma durumu (Y: Evet, N: Hayır)

     Proje Adımları
•	Veri Temizleme ve Eksik Değerlerin İşlenmesi: Veri setinde eksik olan değerlerin tespit edilmesi ve uygun yöntemlerle doldurulması veya temizlenmesi.

•	Veri Görselleştirme: Verilerin özet tablo ve grafiklerle tanıtılması. Özellikle kredi onay oranlarının cinsiyet, medeni durum, eğitim durumu ve mülk alanı gibi faktörlere göre dağılımının incelenmesi.

•	Modelleme:
o	Kredi Onayı Tahmini (Sınıflandırma Problemi): Kredi onay durumunu tahmin etmek için Logistic Regression, Decision Tree ve Random Forest gibi sınıflandırma algoritmaları kullanıldı. Modellerin performansı Accuracy, Precision, Recall ve F1-score gibi metriklerle değerlendirildi.
o	Kredi Miktarı Tahmini (Regresyon Problemi): Kredi miktarını tahmin etmek için Linear Regression, Support Vector Regression ve Random Forest Regression gibi regresyon algoritmaları kullanıldı. Modellerin performansı Mean Squared Error (MSE), Mean Absolute Error (MAE) ve R2 Score gibi metriklerle değerlendirildi.

Sonuç

Bu proje, bankaların kredi onay süreçlerini daha iyi anlamalarına ve optimize etmelerine yardımcı olmayı hedeflemektedir. Veri analizi ve modelleme adımları sayesinde, kredi başvurularının hangi faktörler tarafından etkilendiği ve bu başvuruların sonucunun nasıl tahmin edilebileceği üzerine değerli içgörüler elde edilecektir. Projenin çıktıları, bankaların kredi risklerini daha etkin bir şekilde yönetmelerine ve müşteri memnuniyetini artırmalarına katkıda bulunacaktır.

# LOAN PREDICTION ANALYSIS

     Introduction
     
     This project aims to analyse, clean and model the data related to loan applications of a bank. Within the scope of the project, models were created using different classification algorithms to predict whether loan applications were approved or not. In addition, regression algorithms were also evaluated to predict the loan amount. The aim of the project is to help the bank better understand its loan approval processes and optimise its decision-making processes.

     About the Data Set
     The dataset used in this project contains information on 614 loan applications. The dataset contains various characteristics of the applicants such as demographic information, income levels, credit history and the amount of loans applied for. These characteristics will be associated with the approval status of loan applications.
     The dataset contains the following columns:
1. Loan_ID: Loan application ID
2. Gender: Gender of the applicant
3. Married: Whether the applicant is married or not
4. Dependents: Number of dependants of the applicant
5. Education: Educational status of the applicant (Graduate or Not Graduated)
6. Self_Employed: Whether the applicant is self-employed or not
7. ApplicantIncome: Applicant's income
8. CoapplicantIncome: Income of the co-applicant
9. LoanAmount: Loan amount applied for
10. Loan_Amount_Term: Loan term (in months)
11. Credit_History: Credit history (1: good, 0: bad)
12. Property_Area: Property area of the applicant (Urban, Semi-urban, Rural)
13. Loan_Status: Approval status of the loan application (Y: Yes, N: No)

     Project Steps
- Data Cleaning and Processing of Missing Values: Identifying missing values in the data set and filling or cleaning them with appropriate methods.

- Data Visualisation: Presenting the data in summary tables and graphs. In particular, examining the distribution of loan approval rates according to factors such as gender, marital status, educational status and property area.

- Modelling:
o Loan Approval Prediction (Classification Problem): Classification algorithms such as Logistic Regression, Decision Tree and Random Forest were used to predict loan approval status. The performance of the models was evaluated with metrics such as Accuracy, Precision, Recall and F1-score.
o Loan Amount Estimation (Regression Problem): Regression algorithms such as Linear Regression, Support Vector Regression and Random Forest Regression were used to predict the loan amount. The performance of the models was evaluated with metrics such as Mean Squared Error (MSE), Mean Absolute Error (MAE) and R2 Score.

     Conclusion

    This project aims to help banks better understand and optimise their loan approval processes. Through data analysis and modelling steps, valuable insights will be gained on which factors influence loan applications and how the outcome of these applications can be predicted. The outputs of the project will help banks manage their credit risks more effectively and increase customer satisfaction.


