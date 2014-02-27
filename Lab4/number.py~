class Integer(object):
	def __init__(self,number,numtype):
		self.number=number
		self.type=numtype
	

	def display(self):
		if self.type=="+":
			return self.number
		if self.type=="-":
			self.number=(self.number) * (-1)
			return self.number

class NegativeInteger(Integer):
	def __init__(self,number):
		Integer.__init__(self,number,"-")
	def display(self):
		Integer.display(self)


if __name__=="__main__":
	test=Integer(8,"-")
	test.display()
	potato=NegativeInteger(20)
	potato.display()
	
