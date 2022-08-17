# refactor
# optimize getPotentialJobs method in booking controller the data variable is useless and not used in this method so remove it
# optimazed if | else conditions in this method distanceFeed by using null colesing operator
# further optimized response mode of resendNotifications & resendSMSNotifications method
# modify response of success to failed in storeJobEmail method in BookingRepository
# we can further modify all the BookingRepository condition by using Laravel sync method but right now i dont have database so its hard to manage
# there is alot of if conditions we can handle all of them using trait and helper methods 
