---
layout: page
---

<br/>

# Study/Research Objective

My lab (master’s) is a slightly different kind of lab; it is a lab of course, but also a company. A consulting company to be specific, in my case, close to 100% of all my projects carried out at the lab are for clients like the Korea Electric Power Corporation (KEPCO), the government-owned public corporation (6th largest company in Korea) that supplies power to all Koreans and companies and the Hyundai Elevator, run by the Hyundai Group, only second to Samsung.

Of course, these projects were indeed physically and mentally challenging. Clients demanded outputs fast (which accounts for our once-every-two-weeks progress reports). So, every two weeks, I presented in front of the experts – combustion experts and seasoned mechanical engineers from Hyundai – because I was not only a master’s student but also a main researcher (consultant) for the projects they outsourced to my lab. I must have presented in front of my client-companies at least 30 times.

But I loved these challenges because I was learning and growing. For one project as this was a never-tried project that aims to develop our own gas turbine with our own technology know-how using Deep Learning to prevent all too high false-alarm rate (thanks to this project, Korea became the 5th nation to produce its own gas turbine in the world), I was very eager to learn all that I can so that I can apply the classroom knowledge to the actual field the very next day.

More than anything, however, it was most satisfying knowing that our outputs could end up helping the people.

But I am not entirely satisfied because I have so many unanswered questions – like questions on the gap between the theories I studied in classroom and the questions that came from the field.

And these are the questions that drive me. Specifically, close to 90% if not 100% of my work to this day revolved around the keyword, failure – fault to be specific. Starting from five years ago when I was a junior, I developed a non-destructive testing device for diagnosing defects in bridges at the Korea Institute of Civil Engineering and Building Technology (KICT), responsible for infrastructure research in South Korea. And since then, I continued to focus on the diagnosis and prevention of failures all throughout my bachelor's and master's degrees, resulting in the publication of three SCIE papers.

And I must say that I found this research most fulfilling and incredibly rewarding, conducting research to identify faults that are not readily visible to the naked eyes to help prevent catastrophic accidents. This experience in turn led me to the Prognostics and Health Management (PHM) research to capture signs of failure in dynamic machinery before failures occur, extending beyond static materials. 

Recently, many researchers believe that advanced Deep Learning algorithms will provide answers to the integrity of machine systems. 

However, after three years of in-depth research into diagnostics and prognostics, I realized that an in-depth understanding of the phenomenon and origin of failures is required to provide real solutions. While researching to predict the health state of aircraft turbofan engines using measurement data, I focused on the pure phenomenon of the degradation even though many researchers, at least the ones I had studied, seem to focus mostly on developing ‘deeper and more complex deep learning architectures. By incorporating the physics of failure into handling measurements, I could break the world record while presenting a new viewpoint to PHM academia with datasets on which many researchers have relied for over a decade [1].

However, despite several studies above, research on the origin of failures remains insufficient. I believe that thermodynamic domains must be integrated into the overall diagnostic framework to enhance the reliability of the algorithms I developed. Specifically, I hope to address the lack of failure data through the development of a digital twin model simulating combustion instability phenomena, develop advanced combustion instability diagnostic techniques, and conduct research on active control to mitigate these phenomena. 

As such, my specific research interests are as follows:

**First, I aim to solve the problem of failure data shortage by developing computational fluid dynamics models simulating combustion instability phenomena, which can handle different failure modes and operating conditions.**

Recently, methods such as lean premixed combustor, which drastically reduces the ratio of air to fuel, and increases the ratio of hydrogen to fuel, have gained attention for gas turbine decarbonization [2]. However, as the ratio of air decreases while that of hydrogen increases, gas turbines become extremely susceptible to combustion instability [3]. Combustion instability occurs in various combustion systems ranging from jet engines to gas turbines and can lead to undesirable consequences such as increased noise and catastrophic system destruction through resonance. Therefore, it is essential to predict and prevent it through accurate diagnostic models [4]. Especially, the models simulating faults and degradation from various modes are required because directly inducing faults in combustion systems is costly. Long et al. recently predicted exhaust gas temperature profiles according to failure modes by precisely simulating gas turbine structures [5]. Nam et al., also created an analytical model to predict combustion pressure for optimization purposes [6]. However, analytical research into combustion pressure depending on distinct failure modes has been rarely attempted. Hence, developing a high-fidelity model through additional research to predict combustion pressure according to failure modes would be highly effective. Analyzing the data extracted from this model will enable the development of effective diagnostic models capable of estimating the integrity status and failure locations of the current system, which I believe will be extremely useful in practical settings.

**Second, I intend to reduce computational time for analysis by developing physics-informed neural network (PINN) models to replace computational analytic models of complex systems.**

Highly accurate computational analytic models require substantial computing resources. However, to ensure that diagnostic models are representative under various operating conditions, significant analysis data is required, meaning that reducing the computational time for analysis is a significant challenge. Therefore, PINN, which adds physics terms to complement the accuracy and convergency of artificial neural networks, may be proposed as a replacement for analysis models that require a large amount of computation. In recent, numerous research have been actively conducted to replace complex analysis models, ranging from model flows of fluids [7] to behaviors of electromotors [8]. Especially for fluid analysis, PINN is highly effective due to the large number of meshes required for precise analysis, but there are very few cases where PINN has been applied to multiphysics models such as gas turbines. I want to represent that the PINN model can replace the computational analysis models by developing a PINN model containing universality for various operating conditions with training a few computational analysis results for some operating conditions of complex combustion systems.

**Third, I hope to enhance diagnostic performance by exploring various health indices indicating combustion instability from mechanical engineering perspectives.**

I believe that further research identifying health indices from both combustion engineering and mechanical engineering perspectives will enable more effective diagnostics. Until now, dynamic pressure has been utilized for monitoring gas turbines at power plants, after extracting peak amplitude every second using a fast Fourier transform. However, recent studies have confirmed that root mean square, kurtosis of dynamic pressure, and dynamic temperature have a high correlation with combustion instability [9]. This implies that there may be additional factors reflecting combustion instability in addition to the traditional health indices. Moreover, research on mechanical characteristics (e.g., vibration) changes throughout the entire system caused by combustion instability is not adequately conducted but might be effective for diagnosis. The reason for the assumption that mechanical characteristics are pivotal is that one of the typical symptoms of combustion instability is the amplification of noise, which is a type of vibration [10]. Hence, I want to conduct further research regarding this perspective.

**Fourth, I aim to develop effective diagnostic techniques by combining data obtained from high-speed optical or laser diagnostics with the latest deep learning technologies.**

Previous researchers have used laser diagnostics or optical imaging to diagnose combustion instability[11]. In recent, many researchers have applied various signal processing techniques to optical images to observe them in the frequency domain [12] and used simple deep learning architectures for diagnosis [13]. However, further research in this area is still needed because there have been no attempts to design networks suitable for flame images from a deep learning perspective or to fuse data from various sources including optical images, laser diagnostics results, and mechanical characteristics.

**Lastly, I wish to research real-time active control techniques to mitigate combustion instability based on the obtained diagnosis results.**

I believe that active control techniques to mitigate combustion instability are necessary beyond passive monitoring techniques. One representative method is utilizing sound waves for control, which might be very practical as it can reduce maximum amplitude without changing fuel injection orders [14]. Specifically, in this paper, the amplitude was halved using a simple method of emitting sound waves with opposite phases of the observed vibration pressure signals. Additionally, methods such as controlling chamber wall temperature distribution or utilizing machine learning techniques have been proposed. However, I want to conduct further research in this area because research on the integrated monitoring framework ranging from diagnosis to control is still lacking. And I will continue to conduct research as a professor/scholar who is heavily involved with research while continuing to work with the field per se. 

As a final note, if presented with that precious opportunity to study and to conduct research in the US, I know that I will be steps closer to coming up with insightful studies that hold real-life implications because of my path to this day. 

Although it is true that my work was for the field, still my other foot per se was always in the academia; two SCIE publications and two academic conferences were presented during the master`s course.

And multitasking is my second name since I had to work on these full-time while studying hard. In fact, during four semesters, I took 43 credits, almost maximum number of credits that a student can take – purely because I needed all the knowledge to get insight on my research.

So, I would like to believe that I am an individual who has a good balance - good understanding of the field but also someone who understands the value and the absolute importance of theories - and who can graft the two together by collaborating proactively with diverse experts as I had and which I had always enjoyed as many of these issues are never 2D; instead they are complex issues that requires close collaboration.

<br/>

### References
[1]	Kim, M., Yoo, S., Son, S., Chang, S-Y., & Oh, K-Y., (2024). Deep learning framework of explainable remaining useful life with physics-informed feature transformation. Engineering Applications of Artificial Intelligence (Under review).
[2]	Beita, J., Talibi, M., Sadasivuni, S., & Balachandran, R. (2021). Thermoacoustic instability considerations for high hydrogen combustion in lean premixed gas turbine combustors: a review. Hydrogen, 2(1), 33-57.
[3]	Lee et al. (2004). Phase-Resolved CARS Temperature Measurements in a Lean Premixed Gas Turbine Combustor (Ⅰ)-Effects of Equivalence Ratio on Phase-Resolved Gas Temperature-. Transactions of the Korean Society of Mechanical Engineers - B, 28(10), 1184-1192.
[4]	Oyediran, A., Darling, D., & Radhakrishnan, K. (1995, July). Review of combustion-acoustics instabilities. In 31st Joint Propulsion Conference and Exhibit (p. 2469).
[5]	Long, Z., Zhou, Z., Suo, P., Yao, P., Bai, M., Liu, J., & Yu, D. (2024). Gas turbine circumferential temperature distribution model for the combustion system fault detection. Engineering Failure Analysis, 108032.
[6]	Nam, J., & Yoh, J. J. (2023). Large eddy simulation of combustion instabilities in multiple combustors densely interacting with each other. Applied Thermal Engineering, 220, 119714.
[7]	Sharma, P., Chung, W. T., Akoush, B., & Ihme, M. (2023). A review of physics-informed machine learning in fluid mechanics. Energies, 16(5), 2343.
[8]	Son, S., Lee, H., Jeong, D., Oh, K. Y., & Sun, K. H. (2023). A novel physics-informed neural network for modeling electromagnetism of a permanent magnet synchronous motor. Advanced Engineering Informatics, 57, 102035.
[9]	Joo, S., Choi, J., Lee, M. C., & Kim, N. (2021). Prognosis of combustion instability in a gas turbine combustor using spectral centroid & spread. Energy, 224, 120180.
[10]	Zhang, Y., Liu, X., & Che, D. (2019). Numerical study of the self-excited thermoacoustic vibrations occurring in combustion system. Applied Thermal Engineering, 160, 113994.
[11]	Evans, M. J., & Medwell, P. R. (2019). Understanding and interpreting laser diagnostics in flames: A review of experimental measurement techniques. Frontiers in Mechanical Engineering, 5, 65.
[12]	Nakaya, S., Yamana, H., & Tsue, M. (2021). Experimental investigation of ethylene/air combustion instability in a model scramjet combustor using image-based methods. Proceedings of the Combustion Institute, 38(3), 3869-3880.
[13]	Choi, O., Choi, J., Kim, N., & Lee, M. C. (2020). Combustion instability monitoring through deep-learning-based classification of sequential high-speed flame images. Electronics, 9(5), 848.
[14]	Liu, Y., Li, J., Zhang, T., & Yan, Y. (2021). Active suppression of swirl-stabilized combustion instability. Fuel, 287, 119559.

<br/>
