Variables: Section 1
body_acc_x_train= csv "body_acc_x_train.txt"
body_acc_y_train= csv "body_acc_y_train.txt"
body_acc_z_train= csv "body_acc_z_train.txt"
body_gyro_x_train= csv "body_gyro_x_train.txt"
body_gyro_y_train= csv "body_gyro_y_train.txt"
body_gyro_z_train= csv "body_gyro_z_train.txt"
total_acc_x_train= csv "total_acc_x_train.txt"
total_acc_y_train= csv "total_acc_y_train.txt"
total_acc_z_train= csv "total_acc_z_train.txt"
X_train= csv "X_train.txt"
y_train= csv "y_train.txt"
subject_train= csv "subject_train.txt"
features= csv "features.txt"
totalTR = combined data of subject, y test, and X test for the Training data


Variables: Section 2
X_test= csv "X_test.txt"
y_test= csv "y_test.txt"
subject_test= csv "subject_test.txt"
totalTE = combined data of subject, y test, and X test for the Test data
tot = combined TotalTE and TotalTR


Variables: Section 3
namesmeanSTD<-Names of columns with mean,std, test or subject
meanSTD<- filtered tot by namesmeanSTD


Variables: Section 5
names<-names in meanSTD
totalAVTest<- data frame used to hold all of the activities being built in loop for each test type
totalAVSubject<- data frame used to hold all of the activities being built in loop for each subject
Spmean<- Split meanSTD
sumsplit<- sum of each group
numbr<- number of rows for each group
avg<- average of each group
