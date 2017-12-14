# beefs-quota-watch
Quota Watch utility for BeeGFS

all-in-one package for (soft) quota enforcement. 

once quota is reached (based on pledge), trigger warning email to admin, group czar
if no action is taken, admin can a) block group access altogether (HOW?) or b) start removing files (oldest first).
