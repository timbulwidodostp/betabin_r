# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Beta-binomial model for proportions Use betabin (aod) With (In) R Software
install.packages("aod")
library("aod")
betabin_r = read.csv("https://raw.githubusercontent.com/timbulwidodostp/betabin_r/main/betabin_r/betabin_r.csv",sep = ";")
# Estimation Beta-binomial model for proportions Use betabin (aod) With (In) R Software
betabin_r = read.csv("C:\\betabin_r.csv",sep = ";")
betabin_1 <- betabin(cbind(Dependen, N - Dependen) ~ Independen_1, ~ 1, data = betabin_r)
betabin_2 <- betabin(cbind(Dependen, N - Dependen) ~ Independen_1 + Independen_2, ~ 1, data = betabin_r)
betabin_3 <- betabin(cbind(Dependen, N - Dependen) ~ Independen_1 * Independen_2, ~ 1, data = betabin_r)
betabin_1; betabin_2; betabin_3
# Beta-binomial model for proportions Use betabin (aod) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished