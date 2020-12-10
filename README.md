# Power-of-a-number
The function returns power of an integer
int main()
{
  p= power(3,5);
  cout<<p;
}
int power(int x, int y)
{
  int z;
  for(int i= 1; i<= y; i++)
  {
    z= z*x;
  }
return z;
}
