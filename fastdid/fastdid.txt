# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Fast staggered and flexible Difference-in-Differences (DiD) estimators in Callaway and Sant’Anna’s (2021) Use fastdid With (In) R Software
install.packages("fastdid")
library("fastdid")
fastdid = read.csv("https://raw.githubusercontent.com/timbulwidodostp/fastdid/main/fastdid/fastdid.csv",sep = ";")
# Estimation Fast staggered and flexible Difference-in-Differences (DiD) estimators in Callaway and Sant’Anna’s (2021) Use fastdid With (In) R Software
fastdid <- fastdid(data = fastdid, timevar = "time", cohortvar = "G", unitvar = "unit", outcomevar = "y")
head(fastdid)
# Fast staggered and flexible Difference-in-Differences (DiD) estimators in Callaway and Sant’Anna’s (2021) Use fastdid With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished