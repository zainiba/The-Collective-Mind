# DigitalMediaBot

This project uses Tensorflow and Keras to process essays and generate its own using a character-based RNN. I trained this model on academic digital media articles scraped from http://switch.sjsu.edu/ using Python. 

Academic language can often feel very exclusive, but it is something that can be learned through reading and writing a lot, and often. Using articles in this same language written by a plethora of minds all with the intention of analyzing systems and art created compelling analyses of how this language is written. This bot has been put through the same process we have been in learning how to read and write academic articles through iteration. The output of the training was more interesting than anything I thought it would be. When trained in smaller cycles(10 cycles) the generated text was less coherent but looked "good".

*The Ocens are spearing thas an warman.  Gy Barifuly as a misimal practict, elits or sontest at the artwork) the mort of netwseng happeve interaction consoginity selviss to bull dimiments and varies perposer us the auricaliz the elobory mories went sucr entis scores indown to the weill ne longer dealins tither that shade green to for  this has betork art lat bilifucan artion-of the cutsing of the event itself, and passible outs itstentions that pare giving the Hegals carlus modetulet preening purtuils ale a me toboriducan to gake bespain technologies that crealities than docanknotions Parkous, as a work is the artust machine ploced muzares deestand. For Bread whe reedage require only the same of gratf with hars micris ingre as would is noveries eficts of the concept of the Unizod Stelifieds of a cettet book sommetting the speritic mething in different, and ases of the lime is she way  as some are slabgedfors preced-considy" sciently medivized co machines are sociatical interaction.*

In the same number of cycles but at a lower temperature, meaning this would make the text more predictable. The result was very interesting. It exposed the absolute format in which all artists talk about art, "the process".

*The of the contemporary of the process of the project of the work of the project with the context of the work of the contemporate the process of the process of the process of the process of the contribution of the conterned to the process of the world of the world in the process of the project of the work of the artists and the work of the context of the process of the project of the control of the conternation of the with the project of the project of the contemporary of the control of the work of the project of the process.*

*Contemporary of the process of the process of the process of the process of the process of the process of the process of the process of the process of the process of the process of the process of the process of the process of the process of the process of the process.*

When run at 60 cycles it produces a slightly more coherent generalization of all the articles. 

*Contemporary art and present. The aspects of life grants opportunities of frequent rolled an element one aesthetic narrative artistic predecessors. In September 2010, the ZERO1 Biennial. He only finds their based and resist.  but also a sub-I will evolve significantly over time. As such, I welcome any feedback or comments. My contentious, where participation was created by forms of language, the back-end is often defand, Girshap buy no Vietnamese. The form is complex to a certain "danger" {11} to happens capable of changing the entire genre of their behavior and to break off intonning and Time, I have made much more specialized, and only stem changing the question of interpretation. A third event score by Ken Friedman reads:*

*Contemporary discussion of Aschheim s work in San Jose, California. A symposium kicked off the Biennial. The title of this symposium was Dr. Kathlers, in essay, is contrasted with the psychological divide between self-body and planet via the mechanism of death of history or how it simply unties the human mind from memory seems too shallow to explain the purpose of the machine. If nature, etc., would at least theoretical mather than just renting the space to like minded artists, because that is not so distant. Several independent game titles currently indulge this sentiment. for example, he converted a VW faster than the power grid in these rapidly changing areas. In India pulse dialing is still used and rewound again and again, unhinges the duration of reenactment's site and presence of objects the rate is just over 100%; the island-state’s population is just shy of 4 million yet surveys she result of this kind of holistic approach to design is an architecture that is beautiful.*

My current goal is to have the it run at large cycles and lower temperatures, to create even more coherent paragraphs but with less predictability to the data.

**Credit:**
* https://www.tensorflow.org/tutorials/text/text_generation#train_the_model
* https://scrapism.lav.io/web-scraping-basics/
* http://switch.sjsu.edu/
