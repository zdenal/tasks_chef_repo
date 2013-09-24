# Chef stuff

  * gem install knife-solo
  * gem install librarian-chef ( cookbooks as a bundler gems, what enables update cookbooks by command as in Bundler by bundle gem update ... etd. )
  * knife solo init mychefrepo
  * cd mychefrepo
  * librarian-chef init
  * knife solo prepare root@YOUR_SERVER_IP_OR_ALIAS
   
# Passwd

  * openssl passwd -1 "theplaintextpassword" (generate passwd for put it into file)

