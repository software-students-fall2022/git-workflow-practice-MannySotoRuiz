# Centralized workflow

link: https://www.csoonline.com/article/3060204/mongodb-configuration-error-exposed-93-million-mexican-voter-records.html

Back in 2015, someone unknown had access to the personal information of 93.4 million Mexican voters due to a MongoDB configuration error. This unknown person uploaded the database on Amazon's AWS. This caused the database to be exposed to the public for a mininum of eight days until it was finally discovered a researcher called Chris Vickery. After several attemps of trying to report this issue, he was finally able to reach the Mexican Instituto Nacional Electoral (INE) and they were to have the databse taken offline. Even after investigation, it is still unknown who got access to the databse and uploaded it. 

# Comments from Junyi Dong

It's interesting to see how easily personal information can be leaked when stored online. In this case, it only took a misconfigured database. This is why companies/governments should invest more into security.