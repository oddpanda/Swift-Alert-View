# Swift-Alert-View

Custom Alert View

 let alert = AlertViewController()
        alert.show(self, title: alertTitle, text: alertText, buttonText: "Yes", cancelButtonText:"No", color: UIColor(red: 151.0/255, green: 211.0/255, blue: 207.0/255, alpha: 1.0), iconImage: UIImage(named: "Notificationlogo"))
        alert.actionButton.addTarget(self, action: "alertMethods", forControlEvents: .TouchUpInside)
