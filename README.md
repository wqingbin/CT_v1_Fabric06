# CT_v1_Fabric06

In Fabric 0.6, something changed:
1. In of Init and Invoke func: put the funciton and args parameter into stub. so only 1 parameter was left: stub 
2. delete the Query func. All the call will be routed by Invoke

so changed the CardTransaction.go accordingly