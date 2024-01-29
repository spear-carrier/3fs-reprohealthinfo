# Fear, Friction, and Flooding in Reproductive Healthcare Information Sources Online - A Class Project for Internet Censorship and Online Speech (Winter 2024)

Matt Ryan cnetid: mattryan

I'd like to work alone on this - as I'm missing some of the class meetings, live far from campus, have 2 young kids, etc. From what I understood in lecture, solo projects are fine - please let me know if this won't fly. 

## Project Summary

Trust is a necessary condition for effective public health policy. In a crisis, the importance of not only trust, but of understanding how information control works, is paramount. The COVID-19 pandemic was a clear demonstration of the spectrum of actors transmitting and consuming information online; from public health professionals, to presidents, to YouTube users. It is not clear that there is a consensus of how public health professionals should contend with information control during the next crisis, however, last year three researchers published a paper identifying what that crisis would be: Abortion misinformation. https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10196890/ 

This paper considers information control in the U.S. regarding abortion and "Crisis Pregnancy Centers" (CPCs), or Limited Service Pregnancy Centers (LSPCs). These entities are non for profits, funded by a network of anti-abortion political groups. It's been estimated that CPCs spent over $600 million in 2019. There are an estimated 2400 CPCs in the U.S., far outnumbering healthcare clinics that provide abortions. CPCs are unlicensed and unregulated, and are not subject to the Health Insurance Portability and Accountability Act (HIPPA) laws, raising concerns about  patient information, and legal accountability if that information were to be misused. CPCs have a documented history of propagating false information regarding abortion, such as that the procedure increases women's risk of cancer, invented "syndromes" (https://jamanetwork-com.proxy.uchicago.edu/journals/jama/fullarticle/400644), as well as providing clients with inaccurate information about sexually transmitted infections (STIs) and contraception. It's also been reported that search engine providers are not discriminating between reproductive healthcare clinics staffed by physicians, and CPC alternatives when users search for terms like "abortion care". Eggregiously, the users most targeted by google with ads for CPCs are from low-income households. https://www.theguardian.com/world/2023/feb/07/google-targets-low-income-women-anti-abortion-pregnancy-center-study This paper seeks to explore information control regarding the issue of reproductive healthcare and CPCs by examining SEO data from various geographical locations in the U.S. based on the State policy status of abortion care at that location, as well as by using search results from endpoints in those locations for keywords related to CPC misinformation. I also plan to compare top ten search results for "abortion care" across several geographies, and to classifiy the accuracy of those search results with a set of lableled data of known CPCs. Ideally, the study of information control as it pertains to public health would be used to improve the wellbeing of the public and limit harms caused by private wielders of information control methods who seek to further individual financial, religious, or political goals. The NIH has currently paused a more than $150 million project to improve what is calls "public health communications science" so that the NIH can ". . .reconsider its scope and aims in the context of the current regulatory and legal landscape around communication platforms. Work like this proposed study could one day help inform public health projects like that the NIH had proposed. 

In this paper, I plan to show that for a set of salient search terms related to CPCs, there is geographic variation that correlates with State level policy regarding reproductive healthcare. Set of Terms: {abortion pill reversal, abortion breast cancer, post-abortion syndrome, abortion depression, . . . }


Paragraph 4: At a high level what are the differences in what you are doing, and what others have done? Keep this at a high level, you can refer to a future section where specific details and differences will be given. But it is important for the reader to know at a high level, what is new about this work compared to other work in the area.

The tech-transparency project studied how Google serves ads for CPCs, targeting women from low income households: https://www.techtransparencyproject.org/articles/google-helps-fake-abortion-clinics-target-low-income-women . This study created google accounts based in Phoenix, Atlanta, and Miami and filled out google profile information on income and then compared ad serves across these accounts. 


"The remainder of this paper is structured as follows. . .


## Related Work

This work expands on tech-transparency's previous project. . . 

## Project Preparation and Prerequisites 

To complete this project, I'll need to leverage several sources of data. First, I plan to use a free trial of semrush for SEO related data - https://www.semrush.com/projects/ . Next, I'll use the abortion policy API as structured dataset indicating the legal status of reproductive healthcare on a state by state basis - https://www.abortionpolicyapi.com/ Finally, I'll need to gain access to geographically distributed enpoints capable of conducting search queries in a browswer and transmitting the results to me for colleciton or comparison. I am still finalizing how I will do this, but Google Cloud is what I'm planning on. 

At the end of the data collection, I should have SEO data on keywords such as U.S. based volume of search for the keyword, commonly asked questions involving the keyword, as well as a "difficulty score" indicating how competitive the market for getting placed as search results is for that keyword. Ideally, I'd have this information for several geographical locations, to be determined. 

I should also have a list of top ten results for various reproductive healthcare related search terms, and plan to compare these top ten results across geographies, and to identify when a top ten result for "abortion care" is in fact a CPC using a database of known CPCs - https://reproaction.org/fakeclinicdatabase/ 

## Evaluation

To be written

## Ethics

Reproductive healthcare policy is a political issue and often cited as a complex ethical one. However, I believe that by focusing on the issues of informed consent and attempting to measure information control, that I can safely and ethically begin to contribute to the understanding of how the internnet information environment regarding CPCs is currently disposed in a few areas in the U.S. 
