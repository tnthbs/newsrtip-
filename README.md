# newsrtip-
def newStrip(strs,keyword='^\s+|\s+$'):
    """subsition '' or keyword """
    import re
    newstrRegex = re.compile(keyword)
    newstr = newstrRegex.sub('',strs)
    return newstr

a = newStrip('adf/\nsdfa','\n')
a
