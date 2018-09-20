# 4.11-Intro-to-Programming
autoService = input('Enter desired auto service:\n')
if autoService == 'Oil change':
    print('You entered:', autoService)
    print('Cost of oil change: $%d' %35)
elif autoService == 'Tire rotation': 
    print('You entered:', autoService)
    print('Cost of tire rotation: $%d' %19)
elif autoService == 'Car wash':
    print('You entered:', autoService)
    print('Cost of car wash: $%d' %7)
else: 
    print('You entered:', autoService)
    print('Error: Requested service is not recognized')
