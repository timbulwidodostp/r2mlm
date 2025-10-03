# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Calculating R-squared measures for multilevel models Use r2mlm With (In) R Software
# Compute R-squared values for multilevel models, automatically inputting parameter estimates Use r2mlm With (In) R Software
install.packages("r2mlm")
library("r2mlm")
r2mlm = read.csv("https://raw.githubusercontent.com/timbulwidodostp/r2mlm/main/r2mlm/r2mlm.csv",sep = ";")
# Estimation
# Calculating R-squared measures for multilevel models Use r2mlm With (In) R Software
# Compute R-squared values for multilevel models, automatically inputting parameter estimates Use r2mlm With (In) R Software
r2mlm <- lmer(Reaction ~ Days + (Days | Subject), data = r2mlm)
r2mlm(r2mlm)
# Calculating R-squared measures for multilevel models Use r2mlm With (In) R Software
# Compute R-squared values for multilevel models, automatically inputting parameter estimates Use r2mlm With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished