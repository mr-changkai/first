# first
this is my first repository
the first script i choosed to upload is "lh",which can seprate the nine columns with tab using as "ls -lh|lh",by which,we can do further treatment easily!
write the following contents into a file and put it into where can be call by environment easily
tr -s " "|sed -n 's/^\([^ ]\{1,\}\) \([^ ]\{1,\}\) \([^ ]\{1,\}\) \([^ ]\{1,\}\) \([^ ]\{1,\}\) \([^ ]\{1,\}\) \([^ ]\{1,\}\) \([^ ]\{1,\}\) /\1\t\2\t\3\t\4\t\5\t\6\t\7\t\8\t/gp'
