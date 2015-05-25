# palabra-alreves-
def palabraAlreves(palabra):
        a = 0
        b = len(palabra) -1
        v = 0
        while a <= b:
                if  "E" in palabra[b] or "e" in palabra[b]:
                        v += 1
                print palabra[b],
                b -= 1
        print "\nveces que se repite la letra e", v
