# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# linear mixed model analysis Use lmm (minque) With (In) R Software
install.packages("minque")
library("minque")
lmm = read.csv("https://raw.githubusercontent.com/timbulwidodostp/lmm/main/lmm/lmm.csv",sep = ";")
# Estimation linear mixed model analysis Use lmm (minque) With (In) R Software
lmm=lmm(Dependen~1|Indenpenden_1*Indenpenden_2+Repetition,data=lmm)
lmm$Var
lmm$FixedEffect
lmm$RandomEffect
# linear mixed model analysis Use lmm (minque) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished