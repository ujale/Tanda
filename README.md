# Tanda


Tanda will be acting as a middleware application and as such the authentication endpoint is not exposed for testing. Authentication will be handled in the background as each request is sent from us to Tanda. 
The implementation flow is swerve -> tanda middleware -> tanda service in kenya
