
import openpyxl
dir(openpyxl)
from openpyxl inport workbook
wb = openpyxl.workbook
Sheet= wb.active
Sheet
sheet["A1"] = " Tamil"
sheet["B1"]= "English"
wb.save (filename = "Example.xlsx")
